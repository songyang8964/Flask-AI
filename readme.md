# Flask and Azure AI Integration Project

This project is an experimental implementation of a Python web application using the Flask framework and Azure AI APIs. It is designed to follow the official Microsoft tutorial on building an AI-powered web application using Flask. The tutorial can be found here: [Build a Python web app with Flask and Azure](https://learn.microsoft.com/en-us/training/modules/python-flask-build-ai-web-app/).

## Objective
The primary goal of this project is to:

- Gain hands-on experience with the Flask framework in Python.
- Learn how to integrate Azure AI services into a web application.
- Build and deploy an intelligent web application.

## Features

- **Flask Backend**: Implements a lightweight and modular backend using Flask.
- **Azure AI Integration**: Leverages Azure Cognitive Services APIs to add intelligent functionalities to the application.
- **Web Application**: Creates a dynamic web interface for user interaction.

## Prerequisites
Before running this project, ensure you have the following:

1. **Python**: Version 3.7 or higher installed on your system.
2. **Azure Account**: Access to Azure services and the necessary API keys.
3. **Flask**: Installed in your Python environment.
4. **Other Required Python Libraries**: Refer to the `requirements.txt` file for a list of dependencies.

## Setup Instructions

1. Clone this repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your environment variables:

   - Create a `.env` file in the project directory.
   - Add your Azure API keys and other configuration settings in the following format:

     ```plaintext
     AZURE_API_KEY=<your_azure_api_key>
     FLASK_APP=app.py
     FLASK_ENV=development
     ```

5. Run the Flask application:

   ```bash
   flask run
   ```

6. Open your web browser and navigate to `http://127.0.0.1:5000` to access the application.

## Project Structure

```
project-directory/
├── app.py               # Main Flask application file
├── templates/           # HTML templates for the web interface
├── static/              # Static files (CSS, JS, images)
├── requirements.txt     # List of dependencies
├── .env                 # Environment variables (not included in the repository)
├── README.md            # Project documentation
```

## Acknowledgements

This project was developed following the Microsoft Learn tutorial: [Build a Python web app with Flask and Azure](https://learn.microsoft.com/en-us/training/modules/python-flask-build-ai-web-app/).

Special thanks to the authors and contributors of the tutorial for providing comprehensive guidance.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to extend this README with additional details about your application as it evolves!

