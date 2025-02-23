# buzz5_quiz/README.md

# Buzz5 Quiz Project

This is a Django project named **Buzz5 Quiz**. It is designed to create and manage quizzes.

## Project Structure

The project consists of the following main components:

- **buzz5_quiz/**: The main project directory containing settings and configuration files.
  - **settings.py**: Configuration settings for the Django project.
  - **urls.py**: URL routing for the application.
  - **wsgi.py**: WSGI configuration for deployment.
  - **asgi.py**: ASGI configuration for deployment.

- **quiz/**: The Django app responsible for quiz functionalities.
  - **models.py**: Data models for the quiz application.
  - **views.py**: View functions to handle requests and responses.
  - **admin.py**: Admin interface configuration for the quiz models.
  - **tests.py**: Test cases for the quiz application.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd buzz5_quiz
   ```

3. Create a virtual environment:
   ```
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

5. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Project

To run the development server, use the following command:
```
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your web browser to access the application.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.