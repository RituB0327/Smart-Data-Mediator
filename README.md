**Smart Data Mediator**

Smart Data Mediator is an intelligent data analysis web application built using Flask, Python, and MySQL. It allows users to upload Excel datasets, ask natural-language questions, and automatically generate insights, visualizations, and downloadable reports.

**Features**
📊 Automatic Chart Generation: Creates visualizations (bar, line, pie charts, etc.) for every query.
🧩 Advanced NLP Understanding: Interprets user queries using natural language processing.
🔄 Multiple File Upload: Supports uploading and managing multiple Excel datasets.
🔍 Data Preview: Lets users preview uploaded data before analysis.
🗃️ MySQL Backend: Stores query history, user sessions, and results.
🧾 Downloadable Reports: Generates PDF and Word reports for analyzed data.
💬 Chat with Data: Enables conversational interaction with datasets.
📈 Dashboard View: Displays charts and insights in a clean, interactive dashboard.

**🛠️ Technologies Used**
Frontend: HTML, CSS, JavaScript
Backend: Flask (Python)
Database: MySQL
Libraries: Pandas, Matplotlib, SQLAlchemy, NLP tools (like spaCy or NLTK)

**⚙️ How It Works**
Upload one or more Excel datasets.
Enter a natural language query (e.g., “Show total sales by region”).
The system processes the query using NLP, fetches relevant data, and visualizes results.
Users can download insights as PDF or Word reports.

**Purpose**
The Smart Data Mediator project aims to simplify data analysis by bridging the gap between human language and data logic, making analytics accessible for everyone — no coding or SQL required.

---

 **Installation**

Clone the repository
git clone https://github.com/your-username/smart-data-mediator.git
cd smart-data-mediator
Install required libraries

bash
Copy code
pip install -r requirements.txt
Set up MySQL database

Create a database named smart_data_mediator.

Update database credentials in app.py or config.py.

Run the application

bash
Copy code
python app.py
Open your browser and go to http://127.0.0.1:5000

Project Structure
php
Copy code
Smart-Data-Mediator/
│
├── app.py                  # Main Flask app
├── templates/              # HTML templates
│   └── index.html
├── static/                 # CSS, JS, and images
├── datasets/               # Sample Excel datasets
├── utils/                  # Helper scripts and NLP processing
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
Dependencies
Python 3.13+

Flask

Pandas

Matplotlib

openpyxl

mysql-connector-python

nltk (for NLP processing)

How It Works
Upload your Excel dataset through the web interface.

Enter your query in natural language (e.g., “Show me total sales by region”).

The application processes the query, generates the results, and displays charts.

You can download the results or view them in the dashboard.

Contributing
Contributions are welcome! You can:

Improve query understanding and NLP features.

Add new visualization types.

Enhance the dashboard UI.

Fix bugs and improve documentation.

Please fork the repository and create a pull request with your changes.
