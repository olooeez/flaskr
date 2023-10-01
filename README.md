[![Test](https://github.com/olooeez/flaskr/actions/workflows/test.yml/badge.svg)](https://github.com/olooeez/flaskr/actions/workflows/test.yml)

# flaskr

Flaskr is a web application developed with Flask and SQLite3 to create and manage blog posts in a simple and efficient way.

## Prerequisites

Before getting started, make sure you have the following requirements installed on your machine:

1. **Python**: Python is a programming language used to develop the application. You can download Python from the [official website](https://www.python.org/) and follow the installation instructions for your operating system.

2. **Flask**: Flask is a web microframework for Python that is used in this project to create the web application.

## Installation and Execution

### Step 1: Clone the Repository

Clone this repository to the desired folder on your machine:

```
git clone https://github.com/olooeez/flaskr.git
cd flaskr
```

### Step 2: Set Up the Virtual Environment

It's a good practice to create a virtual environment for the project. In the project directory, you can create a virtual environment using the following command:

```
python -m venv venv
```

Then, activate the virtual environment:

- On Windows:

  ```
  venv\Scripts\activate
  ```

- On macOS and Linux:

  ```
  source venv/bin/activate
  ```

### Step 3: Install Dependencies

Inside the virtual environment, install the project's dependencies using pip:

```
pip install .
```

### Step 4: Configure the Database

The project uses SQLite3 as the database. You can create the database by running the following command:

```
flask --app flaskr init-db
```

### Step 5: Run the Application

Now you can start the Flask application locally with the following command:

```
flask --app flaskr --run
```

The application will be available in your browser at [localhost:5000](http://localhost:5000).

## Contributing

If you wish to contribute to this project, feel free to open a pull request. We welcome all forms of contribution!

## License

This project is licensed under the [MIT License](https://github.com/olooeez/flaskr/blob/main/LICENSE). Please refer to the LICENSE file for more details.
