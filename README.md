
# 📊 AI Data Analysis: Text-to-Chart with Chainlit 🚀

Welcome to the **AI Data Analysis** project! This tool allows non-technical users to easily query data and generate visual charts using simple natural language commands, powered by **Generative AI** and the **Chainlit** web interface. 

## 🎯 Project Overview

This project leverages AI to help users retrieve and visualize data effortlessly by converting natural language into SQL queries and dynamically generating charts in real-time. Just type or speak your query, and the system will do the rest!

Key features include:
- 🗣️ **Text-to-SQL**: Automatically converts natural language inputs into SQL queries.
- 📈 **Dynamic Charting**: Instantly creates visual charts from data, powered by Plotly.
- 🔍 **Semantic Search**: Uses vector stores like Qdrant and FAISS for similar data retrieval.
- 💡 **Actionable Insights**: Provides recommendations based on the retrieved data.

## 🛠️ Tech Stack

- **Chainlit**: Front-end web UI for user interaction.
- **ChatGPT API**: Processes natural language queries and generates SQL.
- **PostgreSQL**: Handles structured data storage and management.
- **Plotly**: Creates dynamic visualizations from query results.
- **LangChain**: Manages the workflow and multi-step operations.
- **Qdrant & FAISS**: Vector stores for semantic search and similarity matching.
- **HuggingFace**: Used for model deployment and scalability.

## 🚀 How to Use

Follow the steps below to get started with the **AI Data Analysis** system:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ai-data-analysis-chainlit.git
cd ai-data-analysis-chainlit
```

### 2️⃣ Install Dependencies

Make sure you have Python installed. Then, install the required dependencies:

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory and add the necessary API keys and environment variables:

```
OPENAI_API_KEY=your-chatgpt-api-key
DATABASE_URL=your-postgresql-database-url
HUGGINGFACE_API_KEY=your-huggingface-api-key
CHAINLIT_PORT=your-desired-port
```

### 4️⃣ Run the Application

Start the Chainlit server to run the application:

```bash
chainlit run main.py
```

### 5️⃣ Interact with the AI

Open your browser and go to `http://localhost:8000` (or the port you configured). You’ll see the Chainlit web interface. Type or speak queries like:

- “What is my revenue for the last quarter?”
- “Show me the monthly sales trend.”
- “Is my revenue increasing or decreasing this year?”

The system will respond with insights and dynamic charts!

### 📊 Example Queries

- **"What is my monthly revenue?"**: Generates a line chart of monthly revenue trends.
- **"Compare this year’s sales to last year’s."**: Creates a bar chart comparing year-over-year sales data.
- **"How is the performance of product X?"**: Retrieves and visualizes specific product data.

## 🛠️ Project Structure

```
📁 ai-data-analysis-chainlit/
├── 📁 data/               # PostgreSQL database setup and schema
├── 📁 models/             # AI model integration (HuggingFace)
├── 📁 utils/              # Helper functions for query and visualization
├── main.py                # Entry point for Chainlit
├── requirements.txt       # Project dependencies
└── README.md              # This file!
```

## ⚡️ Features To Be Added

- 📊 **Support for more file formats**: Query CSV, Excel, and other data sources.
- 🖥️ **Role-based access control**: Different user roles for managing data access.

## 🤝 Contributing

Feel free to fork this repository, submit pull requests, or open issues! Contributions are welcome.

## 📝 License

This project is licensed under the MIT License.

---

🎉 **Enjoy using AI-powered data analysis and visualization with ease!**

