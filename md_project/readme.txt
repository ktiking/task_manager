# Task Manager Project

## Prerequisites
- Python 3.x
- Django 3.x or higher
- Git

## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/task_manager.git
cd task_manager
```

2. Create a virtual environment:
```
python -m venv venv
```

3. Activate the virtual environment:
- On Windows:
```
venv\Scripts\activate
```
- On macOS/Linux:
```
source venv/bin/activate
```

4. Install the required packages:
```
pip install -r requirements.txt
```

5. Apply the migrations:
```
python manage.py migrate
```

6. Create a superuser:
```
python manage.py createsuperuser
```

7. Run the development server:
```
python manage.py runserver
```

8. Open your web browser and go to:
```
http://127.0.0.1:8000/
```

## Usage

- To access the admin panel, go to:
```
http://127.0.0.1:8000/admin/
```
- To view the task list, go to:
```
http://127.0.0.1:8000/tasks/
```
