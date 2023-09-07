```markdown
# Survey Taking App

This is a survey taking application built with Python using Flask, SQLAlchemy, and other libraries. The application allows users to take notes, upload pictures, and create bulletins. The data is then sorted according to date and location.

## Features

- Taking notes
- Uploading pictures
- Creating bulletins
- Sorting data by date and location

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/survey-app.git
    cd survey-app
    ```

2. Install the requirements:
    ```
    pip install -r requirements.txt
    ```

3. Initialize the database:
    ```
    python database.py
    ```

4. Run the application:
    ```
    python main.py
    ```

## File Structure

- `requirements.txt`: Contains the necessary Python libraries for the project.
- `main.py`: The main entry point of the application.
- `survey.py`: Contains the form used for the survey.
- `notes.py`: Contains the model for notes.
- `pictures.py`: Contains the model for pictures.
- `bulletins.py`: Contains the model for bulletins.
- `sort.py`: Contains the functions for sorting data.
- `database.py`: Contains the database configuration.
- `tests.py`: Contains the tests for the application.
- `README.md`: This file.

## Testing

To run the tests, use the following command:

```
pytest tests.py
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
```
