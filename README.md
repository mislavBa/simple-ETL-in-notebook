# ETL Process Notebook

## 📌 Description  
This repository contains a Jupyter Notebook implementing an **ETL (Extract, Transform, Load) process** using Python.  
- **Extract:** Data is collected from an API or other sources.  
- **Transform:** Data is cleaned and processed using `pandas` and visualization libraries.  
- **Load:** Data is stored in a database using SQLAlchemy.  

## 🛠️ Requirements  
Make sure you have the following Python libraries installed:  
```bash
pip install pandas requests python-dotenv matplotlib sqlalchemy seaborn
```

## 🚀 How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Create a **`.env`** file and add your API keys and database connection string.  
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook ETL.ipynb
   ```
4. Run the cells step by step to execute the ETL pipeline.  

## 📦 Libraries Used  
- `pandas` – Data manipulation  
- `requests` – Fetching data from an API  
- `dotenv` – Loading environment variables  
- `matplotlib` & `seaborn` – Data visualization  
- `sqlalchemy` – Database connection  

## 📄 License  
Feel free to use and modify this project as needed.  
