# Recipe API Project

This project is a Django-based API for managing recipes. It provides endpoints for creating, updating, deleting, and retrieving recipes.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/recipe-api-project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd recipe-api-project
    ```

3. Create a virtual environment (recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

5. Install the project dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Django development server:

    ```bash
    python manage.py runserver
    ```

2. Access the API endpoints in your web browser or using tools like Postman:

    - Admin Interface: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
    - API Root: [http://127.0.0.1:8000/recipes/](http://127.0.0.1:8000/recipes/)

## API Endpoints

- `/recipes/`: List all recipes or create a new recipe.
- `/recipes/{id}/`: Retrieve, update, or delete a specific recipe by ID.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
