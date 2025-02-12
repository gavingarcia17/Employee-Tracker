# Employee-Tracker

## Description

Employee Tracker is a command-line application that allows you to manage a company's employee database using Node.js, Inquirer, and MySQL2. The application provides functionality to view, add, update, and delete employees, roles, and departments.

## Features

- View all employees
- Add a new employee
- Update an employee's role
- Update an employee's manager
- View employees by manager
- View employees by department
- View all roles
- Add a new role
- View all departments
- Add a new department

## Installation

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/your-username/employee-tracker.git
    ```

2. Navigate to the project directory:
    ```sh
    cd employee-tracker
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Create a `.env` file in the root directory and add the following:
    ```properties
    DB_HOST=localhost
    DB_PORT=3306
    DB_USER=root
    DB_PASSWORD=newpassword
    DB_NAME=employee_db
    ```

5. Set up the database:
    - Log in to MySQL:
        ```sh
        mysql -u root -p
        ```
    - Create the database:
        ```sql
        CREATE DATABASE employee_db;
        ```
    - Use the database:
        ```sql
        USE employee_db;
        ```
    - Run the schema and seeds files to set up the tables and initial data:
        ```sh
        mysql -u root -p employee_db < schema.sql
        mysql -u root -p employee_db < seeds.sql
        ```

## Usage

1. Start the application:
    ```sh
    npm run start
    ```

2. Follow the prompts to manage the employee database.

## Walkthrough

For a detailed walkthrough of the application, please refer to the following video link:
[Employee Tracker Walkthrough](https://drive.google.com/file/d/1DvF_T1WhOLE4SZeWkqTCieRbIjVn_TZZ/view)

## File Structure
