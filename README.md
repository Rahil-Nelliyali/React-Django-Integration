
## React-Django Integration

This repository demonstrates a simple integration between a React frontend and a Django backend. It serves as a starting point for building a full-stack web application using React and Django.

## Features

- React frontend powered by Create React App
- Django backend with RESTful API
- Communication between React and Django using HTTP requests
- Basic data retrieval from the Django backend API

## Prerequisites

- Node.js (https://nodejs.org)
- Python and pip (https://www.python.org)
- Git (https://git-scm.com)

## Setup

1. Clone the repository:


git clone https://github.com/Rahil-Nelliyali/React-Django-Integration.git
cd react-django-integration


2. Frontend Setup:

   - Navigate to the `frontend` directory:

   cd frontend
 

   - Install the required dependencies:
   
   npm install
 
   - Start the development server:

   npm start
  

   The React frontend will be accessible at http://localhost:3000.

3. Backend Setup:

   - Navigate to the `backend` directory:
   
   cd ../backend
   

   - Create a virtual environment:
   
   python -m venv venv
 

   - Activate the virtual environment:
  
   source venv/bin/activate
 

   - Install the required Python packages:
 
   pip install -r requirements.txt
 

   - Apply database migrations:
  
   python manage.py migrate
  

   - Start the Django development server:
   
   python manage.py runserver
   

   The Django backend will be accessible at http://localhost:8000.

## Usage

- The React frontend communicates with the Django backend API to retrieve data.
- Open your browser and navigate to http://localhost:3000 to see the React app in action.
- The React app will make HTTP requests to the Django backend API at http://localhost:8000/api to fetch data.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.


```

