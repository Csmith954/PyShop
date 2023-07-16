# PyShop

**Project Description:** This is a simple web application built using Python, Django, SQLite, HTML, and Bootstrap. The application allows users to add products to a website, view existing products, and register as a user.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project locally, please follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/project-name.git
   ```

2. Navigate to the project directory:
   ```
   cd project-name
   ```

3. Create a virtual environment:
   ```
   python3 -m venv env
   ```

4. Activate the virtual environment:
   - For Linux/Mac:
     ```
     source env/bin/activate
     ```
   - For Windows:
     ```
     .\env\Scripts\activate
     ```

5. Install the project dependencies:
   ```
   pip install -r requirements.txt
   ```

6. Run the database migrations:
   ```
   python manage.py migrate
   ```

7. Start the development server:
   ```
   python manage.py runserver
   ```

8. Open your web browser and visit [http://localhost:8000](http://localhost:8000) to access the application.

## Usage

- To register a user, click on the "Register" link on the homepage and fill in the required information.
- To add a product, click on the "Add Product" link in the navigation menu and provide the necessary details.
- To view existing products, click on the "Products" link in the navigation menu.

## Features

- User registration: Users can create an account to access the application.
- Add product: Users can add new products to the website.
- View products: Users can view a list of all existing products.

## Technologies Used

- Python: Programming language used to build the application.
- Django: Web framework used to develop the application.
- SQLite: Relational database used to store product and user information.
- HTML: Markup language for creating the structure of web pages.
- Bootstrap: CSS framework for designing responsive and visually appealing web pages.

## Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request detailing your changes.

## License

This project is licensed under the [MIT License](LICENSE).
