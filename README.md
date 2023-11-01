# Lemon Web Application - META Backend Developer Specialization

![Lemon Web Application](restaurant/static/img/logo.png)

## Description

Lemon Web Application is a dynamic web application built using Django as part of the Meta Backend Developer Specialization. The application allows users to manage their lemonade stand business, including adding new products and managing inventory. It provides a user-friendly interface for both administrators and regular users.

## Features

- User Authentication: Secure user registration and login functionality.
- Product Management: Add, update, and delete products with name, price, and description.
- Inventory Tracking: Manage product inventory levels and track stock availability.
  
## Technologies Used

- Django: A powerful web framework for building web applications in Python.
- Python: The programming language used for backend development.
- Django Rest Framework: An extension for building RESTful APIs with Django.
- MySql: A robust relational database used to store application data.
- HTML, CSS, JavaScript: Frontend technologies for creating the user interface.

## Installation and Setup

1. Clone the repository from [GitHub](https://github.com/yourusername/lemon-web-app).
2. Create and activate a virtual environment.
3. Install the required dependencies using the following command:
   ```
   pip install -r requirements.txt
   ```
4. Set up the PostgreSQL database and configure the database settings in `settings.py`.
5. Apply migrations using the following command:
   ```
   python manage.py migrate
   ```
6. Create a superuser for the Django admin:
   ```
   python manage.py createsuperuser
   ```
7. Run the development server:
   ```
   python manage.py runserver
   ```
8. Access the application in your web browser at http://localhost:8000/.

## Usage

1. Create a new account or log in if you already have one.
2. As an administrator, you can manage products, view sales data, and track inventory levels.
3. As a regular user, you can view products, add them to the cart, and place orders.
4. Use the search functionality to find specific products by name or description.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to create a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for checking out Lemon Web Application. We hope you find it useful and enjoy using it! If you have any questions or need assistance, please feel free to contact us. Happy coding! 🍋
