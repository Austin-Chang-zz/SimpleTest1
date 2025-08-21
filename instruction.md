# Hallo World Flask App

This is a simple Flask application that returns "Hallo World!".

## Getting Started

1. Make sure you have Flask installed. You can check this in your `pyproject.toml`, which should include:
    ```toml
    dependencies = [
        "flask>=3.1.1",
    ]
    ```

2. The main code is in `main.py`. Here’s the code inside:

    ```python
    from flask import Flask

    app = Flask('app')

    @app.route('/')
    def hello_world():
        return 'Hallo World!'

    app.run(host='0.0.0.0', port=5000)
    ```

3. To run the application, you can simply click on the **Run** button in Replit. The app will be accessible on port 5000.

## Accessing the App

Once it's running, you can access the app by navigating to:You should see "Hallo World!" displayed in the browser.