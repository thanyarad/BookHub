# BookHub - An online Bookstore website

## Introduction

BookHub is a web application designed to provide a seamless experience for book enthusiasts. Users can browse through a variety of books, add them to their cart, and manage their personal accounts. The application includes features such as user registration, login, and a shopping cart system.

## Features

- **User Registration and Login**: Secure user registration and login functionality.
- **Book Browsing**: Browse through a selection of books.
- **Shopping Cart**: Add books to the cart and view cart details.
- **Blog Section**: A blog section for book-related articles.

## Directory Structure

```
loginphp/
├── banner.jpg.jpg
├── blog.html
├── book/
├── BookHub/
├── cart.html
├── css/
├── header.html
├── headerstyle.css
├── image/
├── indexstyle.css
├── Login.html
├── login.php
├── register.php
├── shop.html
├── sproduct.html
├── stylelogin.css
```

### Key Files and Directories

- **blog.html**: Blog page for book-related articles.
- **cart.html**: Shopping cart page.
- **header.html**: Header template for the website.
- **headerstyle.css**: CSS file for the header styling.
- **indexstyle.css**: CSS file for the main index page styling.
- **Login.html**: Login page.
- **login.php**: Backend PHP script for handling user login.
- **register.php**: Backend PHP script for handling user registration.
- **shop.html**: Shop page displaying available books.
- **sproduct.html**: Single product page.

## Setup and Installation

1. **Clone the repository**: 
    ```sh
    git clone <repository_url>
    ```

2. **Navigate to the project directory**:
    ```sh
    cd loginphp
    ```

3. **Set up your web server**:
    - Ensure you have a web server like Apache or Nginx installed.
    - Place the `loginphp` directory in your web server's root directory.

4. **Configure the database**:
    - Create a MySQL database and user.
    - Import the provided SQL file (if available) to set up the necessary tables.

5. **Update database configuration**:
    - Modify the PHP files (`login.php`, `register.php`) to include your database credentials.

6. **Start your web server**:
    - Ensure your web server is running and navigate to `http://localhost/loginphp/Login.html` to access the login page.

## Usage

1. **Register a new account**:
    - Navigate to the registration page and create a new account.

2. **Log in**:
    - Use your credentials to log in to the application.

3. **Browse books**:
    - Explore the books available in the shop and add them to your cart.

4. **View Cart**:
    - Check the books added to your cart and proceed to checkout.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Please ensure your code follows the project's coding standards.
