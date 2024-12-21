
# Django CSV Analysis Web App

This project is a Django-based web application that allows users to upload CSV files, perform data analysis using pandas and numpy, and visualize the results on a user-friendly web interface.

## Features

- **File Upload**:  
  Users can upload CSV files for processing.

- **Data Analysis**:  
  The application performs the following tasks:
  - Displays the first few rows of the data.
  - Calculates summary statistics (mean, median, standard deviation) for numerical columns.
  - Identifies and handles missing values.

- **Data Visualization**:  
  The application generates basic visualizations:
  - Histograms for numerical columns.
  - Displays the plots directly on the web interface.

- **User-Friendly Interface**:  
  Built using Django templates for a clean and simple UI.

---

## Technologies Used

- **Backend**: Python, Django  
- **Libraries**: pandas, numpy, matplotlib  
- **Frontend**: HTML, CSS (via Django templates)  

---

## Setup Instructions

Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd csvdata_project
```

### 3. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Migrations

```bash
python manage.py migrate
```

### 6. Run the Server

```bash
python manage.py runserver
```

### 7. Access the Application

Open your browser and visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## Sample Usage

1. **Upload a CSV File**:  
   Use the file upload feature on the homepage to upload a CSV file.

2. **View Data Analysis**:  
   Once the file is uploaded, view the processed data including:
   - First few rows of the dataset.
   - Summary statistics.

3. **Visualize Data**:  
   View generated histograms for numerical columns directly on the web page.

---

## Sample CSV File

The repository includes a sample CSV file (`sample_data.csv`) for testing purposes. You can also upload your own CSV files for analysis.

---

## Contact

If you have any questions or need further assistance, feel free to contact me.
