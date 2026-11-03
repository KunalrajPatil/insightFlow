# InsightFlow – E-Commerce Analytics Dashboard

InsightFlow is a full-stack analytics platform designed to explore e-commerce business data and uncover insights that support better decision-making. It brings together sales performance, customer trends, product profitability, returns, and shipping analytics in one interactive dashboard.

Rather than simply presenting numbers, InsightFlow focuses on understanding business performance, identifying potential issues, and highlighting areas that require attention.

## Overview

E-commerce businesses generate large amounts of operational data, but turning that data into meaningful business insights requires more than basic reporting.

InsightFlow addresses this by combining SQL-based analytical queries with an interactive dashboard, allowing users to investigate business metrics and understand the factors influencing performance.

## Key Features

- **Return Analysis:** Examine product returns across different regions and managers to identify unusual return patterns.
- **Customer Insights:** Identify top revenue-generating customers across states using ranking techniques.
- **Shipping Analytics:** Evaluate average delivery times and late shipment percentages across shipping methods.
- **Sales Trends:** Analyze monthly sales performance and month-over-month growth to identify seasonal patterns.
- **Profitability Analysis:** Compare profitable and loss-making products to understand their contribution to overall business performance.
- **Pareto Analysis:** Identify products responsible for a significant share of total profits or losses.
- **Interactive Dashboard:** Explore business metrics through visualizations and detailed analytical views.
- **Insight Cards:** Access summarized findings and recommended business actions through flip-card interactions.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Backend | Python, FastAPI |
| Database | SQL |
| Query Techniques | CTEs, Joins, Window Functions, Aggregations |
| Data Visualization | Interactive dashboard visualizations |

## SQL Concepts Implemented

The analytical layer uses SQL to transform raw business records into meaningful information.

Some of the major concepts implemented include:

- **Joins:** Combining information from multiple relational tables.
- **Conditional Aggregation:** Calculating business metrics using conditional logic.
- **Common Table Expressions (CTEs):** Structuring complex queries into manageable steps.
- **Window Functions:** Implementing customer rankings, running totals, and analytical comparisons.
- **Date Functions:** Performing monthly and time-based performance analysis.
- **Percentage Calculations:** Measuring return rates, delivery delays, and profitability.

## Project Structure

```text
InsightFlow/
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── ... 
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```

*Note: The structure above provides a high-level overview. Additional files and modules may vary depending on the implementation.*

## Getting Started

Follow these instructions to run InsightFlow locally.

### Prerequisites

Make sure you have installed:

- Python 3.10 or later
- Node.js and npm
- A compatible SQL database
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/InsightFlow.git
```

Navigate to the project directory:

```bash
cd InsightFlow
```

### 2. Set Up the Backend

Navigate to the backend folder:

```bash
cd backend
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Configure your database connection using the project's backend configuration and ensure the required database and tables are available.

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

The backend will be available at:

```text
http://127.0.0.1:8000
```

FastAPI interactive API documentation:

```text
http://127.0.0.1:8000/docs
```

### 3. Set Up the Frontend

Open another terminal and navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the React development server:

```bash
npm start
```

The frontend will run at the local development URL displayed in your terminal.

## Business Questions Explored

InsightFlow is built around practical business questions:

1. Which regions and managers have higher-than-usual product return rates?
2. Who are the highest revenue-contributing customers in each state?
3. Which shipping methods experience longer delivery times and more delays?
4. How does sales performance change from one month to another?
5. Which products contribute most to overall profits and losses?
6. How concentrated are profits and losses among a small group of products?

## Project Objectives

- Apply advanced SQL concepts to practical business scenarios.
- Develop an understanding of e-commerce sales and operational performance.
- Build an interactive full-stack analytics application.
- Convert raw data into meaningful and actionable business insights.
- Demonstrate how data analytics can support business decisions.

## Future Improvements

Potential enhancements include:

- Advanced filtering and cross-dashboard comparisons.
- Downloadable analytical reports.
- More detailed customer segmentation.
- Additional sales forecasting capabilities.

## Author

**Kunalraj Patil**

Developed as a hands-on project combining SQL, Python, backend development, frontend development, and business analytics.

---

*InsightFlow – Turning Business Data into Meaningful Insights.*