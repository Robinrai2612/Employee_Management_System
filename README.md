
# Employee Management System Using Python and MySQL

Manage employee records efficiently with this Employee Management System, a Python program backed by a MySQL database. This system offers essential functions for adding, displaying, updating, promoting, removing, and searching for employee records.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Add Employees:** Easily input employee details, including name, email, phone number, address, post, and salary.

- **Display Records:** View a list of all employee records in an organized manner.

- **Update Information:** Modify employee records by updating their email, phone number, and address.

- **Promote Employees:** Increase an employee's salary with a simple promotion function.

- **Remove Records:** Delete employee records when they are no longer needed.

- **Search Functionality:** Find employee records based on their unique employee ID.

- **User-Friendly Interface:** A menu-driven interface makes navigation and data management a breeze.

## Prerequisites

Before you get started, ensure you have the following components installed on your system:

- **Python (3.x recommended):** [Download Python](https://www.python.org/downloads/)

- **MySQL Database:** [Download MySQL](https://dev.mysql.com/downloads/mysql/)

- **MySQL Connector for Python:** You can install it using pip:
  ```bash
  pip install mysql-connector-python

## Getting Started

### Clone the Repository:
> git clone https://github.com/yourusername/employee-management-system.git

### Navigate to the Project Directory:
> cd employee-management-system
### Update MySQL Connection Details:
> con = mysql.connector.connect(host="localhost", user="root", password="your_root_password", database="employee")
Replace "your_root_password" with your MySQL root password.

## Usage

To run the Employee Management System, execute the following command:

> python employee_management_system.py

## Database Setup
Before using the system, you need to set up the MySQL database and table. Follow these steps:

1. Log in to MySQL as the root user:
> mysql -u root -p

2. Create the 'employee' Database:
> Create the 'employee' Database:

3. Switch to the 'employee' Database:
> Switch to the 'employee' Database:

4. Create the 'empdata' Table:
> CREATE TABLE empdata (
    Id INT PRIMARY KEY,
    Name VARCHAR(255),
    Email_Id VARCHAR(255),
    Phone_no VARCHAR(15),
    Address VARCHAR(255),
    Post VARCHAR(255),
    Salary FLOAT
);


Now, you can use the Employee Management System with the MySQL database.

## Contributing
If you would like to contribute to this project or report issues, please follow the guidelines outlined in CONTRIBUTING.md.
