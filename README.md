# E-Library Project

Welcome to the E-Library project, a collaborative effort by UBi, Joseph, Frankelly, and Ayan Nicholas. This project represents our journey into backend engineering, where we've created a user-friendly E-Library application to share, manage, and explore various digital documents.

## Table of Contents

- [Project Overview](#project-overview)
- [Contributors](#contributors)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Project Overview

The E-Library project is designed to facilitate the sharing and organization of digital documents, including PDFs, Word, and Docx files. Built using a stack of technologies that complement our learning journey, this project embodies our dedication to mastering backend engineering.

## Contributors

- **Ubi, Joseph** - *Backend Developer*
- **Frankelly, Ozonwo** - *Database Specialist*
- **Ayan Nicholas** - *Frontend Developer*

## Technologies Used

Our choice of technologies reflects our commitment to mastering the fundamentals of web development while creating an efficient and user-friendly application:

- **HTML** - For structuring the web pages.
- **CSS** - For styling the user interface.
- **JavaScript** - For dynamic and interactive features.
- **PHP** - For server-side scripting and handling backend logic.
- **MySQL** - As the relational database management system.
- **Apache** - As the web server to serve our application.

## Features

1. **Secure File Uploads**: The E-Library allows users to upload PDF, Word, and Docx files securely. This feature was implemented to ensure that only valid document types are accepted.

2. **Efficient Database Management**: We have integrated MySQL as our database system, providing efficient storage and retrieval of document-related information.

3. **User-Friendly Interface**: The user interface is designed to be simple and intuitive, ensuring that users can easily navigate and find the documents they need.

## Installation

To set up the E-Library project locally, follow these steps:

1. Install [XAMPP Server](https://www.apachefriends.org/index.html) if not already installed.

2. Start the Apache and MySQL modules in XAMPP.

3. Visit `http://localhost/phpmyadmin` to access PHPMyAdmin. Create a new database named 'newdb', and within it, create a table named 'bookdb' with seven fields: `bookname`, `bookdesc`, `bookauthor`, `booklang`, `bookfile`, `uploadername`, `uploaderemail`. Ensure that all fields have the type `varchar`.

4. Download the project files and place them in the `XAMPP\htdocs\` directory.

5. Inside the `htdocs` folder, create a directory named 'files' where uploaded books will be stored.

6. Access the project by visiting `http://localhost/your_project_directory_name/index.html` in your web browser.

## Usage

- Users can upload documents using the 'Upload Document' button.
- Uploaded documents are stored in the 'files' directory.
- The database manages document metadata such as name, description, author, and language.
- The E-Library provides a user-friendly interface to browse and download documents.


We hope you find our E-Library project both educational and functional. We invite you to explore, contribute, and adapt it to your own learning journey and projects. If you have any questions or suggestions, please feel free to reach out to any of the contributors.

**Happy learning and coding!**



![e-library](https://github.com/Joe-metry/Portfolio_MVPs/assets/117749127/d5fd545b-6d0f-46b5-a506-876e2788f862)

