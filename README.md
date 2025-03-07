# task_manager
CC105 Midterm Project

## Prerequisites
- Python 3.x
- Django 3.x or higher
- MySql(MariaDB)
- Git

## Installation

1. Clone/Download the repository:
```
git clone https://github.com/yourusername/task_manager.git
cd task_manager

Create a folder then paste the folder you got from the repository inside.
```

2. Import the Database you got from the GitHub Repository called: "tasks.sql" inside the PhpMyAdmin in the SQL Import Section

3. Create a virtual environment:
```python -m venv venv```

4. Activate the virtual environment:
```venv\Scripts\activate```

5. Navigate to the folder
```cd task_manager```

5. Install the required packages:
```pip install mysqlclient```

6. Apply the migrations:
```python manage.py migrate```

7. Run the development server:
```python manage.py runserver```

## Usage
- To view the task list, go to:
http://127.0.0.1:8000/tasks/

