# **Time Series Analysis Full stack App**

#### **Objective:**

*Create a web application that allows users to upload time-series data in Excel or CSV format, parse and clean the data, store it in a database, analyze it, and display interactive charts with time delta selection functionality.*

---

### **Requirements:**

#### **Frontend:**

* **Technology Stack:** React (or Angular/Vue.js) for the web portal.
* **Features:**

  * **File Upload Component:** Allow users to upload Excel/CSV files.
  * **Data Table:** Display the cleaned data.
  * **Interactive Charts:**

    * Line chart for trends over time.
    * Other visualizations (e.g., bar or scatter plots) for insights.
  * **Time Delta Selection:**

    * Dropdown or date-picker range to filter the displayed data by a specific time range.

---

#### **Backend:**

* **Technology Stack:** Python (FastAPI / Flask / Django).
* **Features:**

  * **Parse and Validate Uploaded Files:**

    * Use libraries like pandas (Python) for parsing.
  * **Data Cleaning:**

    * Remove null and empty values.
    * Apply regularization (e.g., standardizing date formats, normalizing numerical values).
  * **Store Data in Database:**

    * Use PostgreSQL/MySQL for relational data or MongoDB for flexible schema.
  * **Perform Analysis:**

    * Calculate summary statistics (mean, median, trends).
    * Perform time-based aggregations (daily, weekly, monthly).
  * **API Endpoints:**

    * Endpoint to upload and process data.
    * Endpoint to fetch cleaned and analyzed data for frontend charts.
    * Endpoint to filter data based on time delta.

---

### **Database:**

* **Schema:**

  * **Raw Data Table:**

    * Store raw data for reference.
  * **Cleaned Data Table:**

    * Store cleaned and transformed data.
  * **Analysis Results Table:**

    * Store computed metrics like trends, averages, etc.

---

### **Deliverables:**

1. Web portal with an intuitive UI for uploading, filtering, and visualizing data.
2. Clean and modular code for frontend and backend.

---

### **Additional Mandatory Features:**

* Export cleaned or analyzed data to CSV/Excel.
* Use advanced analysis techniques (e.g., clustering, forecasting).
* Deploy the application on a cloud platform like AWS/GCP/Azure or a hosting service like Heroku/Netlify.

