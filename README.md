Flask Calculator Project
Overview
This is a basic calculator web application built using Python's Flask framework. The application allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division, as well as more advanced operations such as square root, square, and reciprocal. The frontend is built using HTML and CSS, while the backend uses Python with Flask for handling calculations and requests.

Features
Supports basic arithmetic operations (addition, subtraction, multiplication, division).
Supports advanced mathematical functions (square, square root, reciprocal).
Error handling for division by zero and invalid inputs.
Responsive and user-friendly interface.
Project Structure
The project directory contains the following structure:
Calculator using Flask/
│
├── static/
│   ├── readme.txt
│   ├── styles.css           # Stylesheet for the frontend
│
├── templates/
│   ├── about.html           # About page for the app
│   ├── base.html            # Base template for other HTML files
│   ├── index.html           # Main page where the calculator is displayed
│   ├── readme.txt
│
├── app.py                   # Main Flask app where the server is initialized
├── evaluator.py             # Contains the functions for evaluating expressions
├── logic.py                 # Handles the request processing logic
├── routes.py                # Manages the routes and links templates to logic
├── README.md                # Project documentation



Dependencies
To run this project, you need the following dependencies:

Python 3.x
Flask

You can install Flask using pip:

pip install Flask

Setup and Installation
  Clone the repository:

  git clone https://github.com/shaileshkry/Calculator.git

Navigate to the project directory:

  cd Calculator/Calculator using Flask

Install the required dependencies:

  pip install Flask
Run the application:
  python app.py

Open your browser and go to:
  http://127.0.0.1:5000/

Usage
Open the main page to use the calculator.
Enter an arithmetic expression (e.g., 5 + 2 * 3) and press enter or click on "Calculate".
The result will be displayed on the screen.
You can navigate to the About page to learn more about the application.

Code Explanation
app.py
This file is the entry point of the Flask app. It imports the routes and initializes the Flask server. It also defines the URL routing for the home and about pages.

evaluator.py
This file contains the logic for all arithmetic and advanced mathematical operations. It defines functions for addition, subtraction, multiplication, division, square, square root, and reciprocal operations. It also handles error cases like division by zero and invalid inputs.

routes.py
This file defines the routes for the web application. It links the templates to the logic for processing requests.

logic.py
This file handles the form processing and calls the evaluate_expression function from evaluator.py to process the entered expression and return the result.

templates/
Contains the HTML templates for the app:

index.html: The main calculator page with input and result display.
about.html: A page describing the project.
base.html: A base template with common HTML elements like headers and footers.
static/
Contains the static files such as the CSS stylesheet for styling the web pages.

Contributing
Feel free to fork this project, create your own features, or submit pull requests. Contributions are always welcome!

License
This project is open-source and available under the MIT License.


