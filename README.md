# data_analyst_AI_Agent
This is a Data Analyst AI Agent built using LangChain and Google Gemini API. It allows users to upload data files (CSV, XLSX, PDF), ask questions about the data, and generate visualizations. The agent maintains conversational memory for context-aware interactions and provides insights through natural language queries.

##Features

    1. File Support: Upload and analyze data from CSV, XLSX, and PDF files.

    2. Conversational Memory: Maintains context across queries for seamless interactions.

    3. Data Visualization: Generates interactive charts (bar, line, pie, scatter) using Plotly.

    4. Natural Language Queries: Ask questions about the data in plain English.

    5. Error Handling: Provides clear error messages for unsupported file types or invalid queries.

##How It Works

    1. Upload a File: Use the file upload widget to provide your data (CSV, XLSX, or PDF).

    2. Ask Questions: Type your query in the input box (e.g., "What are the top 5 sales regions?").

    3. Visualize Data: Use keywords like "visualize," "chart," or "graph" to generate plots.

    4. Conversational Context: The AI remembers previous queries for context-aware responses.

##Installation

    Clone the repository:

    git clone https://github.com/your-username/data-analyst-ai-agent.git
    cd data-analyst-ai-agent

    Install dependencies:

    pip install pandas numpy pdfplumber plotly ipywidgets google-generativeai langchain

    Set up Google Gemini API:

        Obtain an API key from Google AI Studio.

        Replace the placeholder in the code with your API key:
        
        genai.configure(api_key="your-api-key-here")

    Run the Jupyter Notebook:

    jupyter notebook

##Usage

    Open the Jupyter Notebook and run all cells.

    Upload a file using the file upload widget.

    Ask questions or request visualizations in the query input box.

##Example Queries

    Data Analysis:

        "What is the average sales value?"

        "Show the top 5 products by revenue."

    Visualizations:

        "Visualize sales by region."

        "Create a bar chart for monthly sales."

##Dependencies

    pandas

    numpy

    pdfplumber

    plotly

    ipywidgets

    google-generativeai

    langchain

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
Acknowledgments

    LangChain for conversational memory and AI integration.

    Google Gemini API for natural language processing.

    Plotly for interactive visualizations.
