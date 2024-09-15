# DjangoReactTemplate

## Overview

This project is a template for building web applications using Django as the backend framework and React for the frontend. 
The template includes configurations for rendering React components within Django templates.


## Prerequisites
- Python 3.x
- Node.js and npm
- Django 5.x

## Installation
1. **Clone the repository:**

   ```
   git clone https://github.com/CyrusNchege/DjangoReactTemplate.git
   cd DjangoReactTemplate

   ```

2. **Backend Setup:**


- This Setup is for when You do not want to use Docker,
if you prefer Docker, there is a branch in this Repo for that.

- Create a virtual environment and activate it(Depend on which platform you are in or package you use)


   ```

   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

   ```

- Install the required Python packages:

   ```
   pip install -r requirements.txt
   ```

- Apply migrations:
   ```
   python manage.py migrate
   ```

- Start development Server
   ```
   python manage.py runserver
   ```

2. **Frontend Setup:**



   ```
   cd frontend

   ```

- Install Npm Packages

   ```
   npm install
   ```

- Run Development Server

   ```
   npm run dev
   ```


## Usage

You can now access the application by visiting `http://localhost:8000` in your browser.

For improvements, you can edit the React components in the `frontend/src/components` directory.

You can Create a new Django app and expose you api endpoints.

You can Improve the handling of sensitive data by using environment variables.

You can Configure the project to use a database of your choice.
