<h1 align="center" style="color: #4285F4"> Enployees CRUD App </h1>

## <span style="color: #4285F4"> Project Description

This repository contains the source code for a fullstack web application developed as part of a web development course. The front-end is built using React JS, while the back-end is developed in Python Django. The database is managed using PostgreSQL.

## <span style="color: #4285F4"> Key Features

- Routing and interactive navigation menu in React
- Displaying data in a Bootstrap table
- Implementing a modal window with dropdowns and date pickers
- Uploading and storing photos on the backend server

## <span style="color: #4285F4"> Instructions for Use

1. **Clone or Download:** Clone this repository or download the ZIP archive.
2. **Set Up Python Virtual Environment:**
```bash
python -m venv env
source env/bin/activate  # Pe Windows: env\Scripts\activate
```
3. **Install Backend Dependencies:**
```bash
cd DjangoAPI
pip install -r requirements.txt
```
4. **Configure Environment Variables:** Edit the `settings.py` file in the `DjangoAPI` directory and update the following variables with your PostgreSQL database details:
```bash
NAME=database name
USERNAME=postgres username
PASSWORD=postgres password
```
5. **Start Backend Server:**
```bash
python manage.py runserver
```
6. **Install Frontend Dependencies:**
```bash
cd react-fe
npm install
```
7. **Start Frontend Server:**
```bash
npm start
```
8. **Access the Application:** Access the application in your web browser at the following address: `http://localhost:3000`




## <span style="color: #4285F4"> Authors

**Forminte Andrei-Gabriel**

- [Profile](https://github.com/andrey100f)

