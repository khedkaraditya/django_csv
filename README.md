# django_csv

A Django-based web application that allows users to upload CSV files, performs data analysis using pandas and numpy, and displays the results and visualizations on the web interface.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip (Python package installer)
- virtualenv

### Installation

1. *Clone the repository*:
   
   git clone https://github.com/khedkaraditya/django_csv.git
   cd project

   Create and activate a virtual environment:


Copy code
python3 -m venv venv
source venv/bin/activate

Install dependencies:
  pip install -r requirements.txt


Set up the database:
   python manage.py migrate

Run the development server:
  python manage.py runserver

Access the application:
Open your web browser and navigate to http://127.0.0.1:8000/.
