# Flask Blog App

A Flask-based web application for managing and publishing blog posts. Users can create, update, delete, and view blog posts, with secure login functionality.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Overview

This project is a blog application built using Flask. It allows users to manage their blog posts, providing features for creating, editing, deleting, and viewing posts. The application includes user authentication to ensure that only authorized users can manage their posts.

## Features
- **Create Posts**: Users can create new blog posts with a title and body.
- **Update Posts**: Users can update existing blog posts.
- **Delete Posts**: Users can delete blog posts.
- **View Posts**: Users can view a list of all blog posts.
- **User Authentication**: Users must log in to create, update, or delete posts.
- **Responsive UI**: User interface designed for a seamless experience.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/flask-blog-app.git
    cd flask-blog-app
    ```

2. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Initialize the database:**

    ```bash
    flask init-db
    ```

4. **Run the application:**

    ```bash
    flask run
    ```

## Usage

1. **Access the Application**: Open your browser and go to `http://127.0.0.1:5000/` to view the blog.

2. **Login/Register**: Use the login or registration pages to create an account or log in.

3. **Create/Edit/Delete Posts**: Once logged in, you can create, update, and delete posts.

## Technologies Used

- **Flask**: A micro web framework for Python.
- **SQLite**: A lightweight database used for development.
- **Python**: The programming language used for this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
