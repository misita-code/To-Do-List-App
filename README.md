# To-Do CLI Application

## Description

The **To-Do CLI Application** is a command-line interface (CLI) tool designed to help users manage tasks efficiently. It supports user management, task categorization, and task tracking, utilizing Python and SQLAlchemy for data persistence.

## Features

- Manage Users
- Manage Categories
- Manage Tasks
- Exit the application

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd To-Do-List-App
   ```
2. Install dependencies using Pipenv:
   ```sh
   pipenv install
   ```
3. Activate the virtual environment:
   ```sh
   pipenv shell
   ```
4. Run the application:
   ```sh
   pipenv run python -m cli.main
   ```

## Usage

Upon running the application, the following menu is displayed:

```
=== TO-DO CLI Application ===
1. Manage Users
2. Manage Categories
3. Manage Tasks
4. Exit
```

Users can select options to manage their to-do lists effectively.

## Notes

- If you encounter a warning related to Pipenv running within a virtual environment, it is safe to ignore. However, you may set `PIPENV_IGNORE_VIRTUALENVS=1` to force Pipenv to create its own virtual environment.

## Technologies Used

- Python
- SQLAlchemy
- Pipenv

## License

This project is licensed under the MIT License.

## Author

Developed by [Misita Wallace]\
\
Running the app \
phase3wallace\@wallace-hp-elitebook-745-g6:\~/Development/code/phase3/To-Do-List-App\$ pipenv run python -m cli.main

Courtesy Notice:

Pipenv found itself running within a virtual environment,  so it will automatically use that environment, instead of  creating its own for any project.&#x20;

You can set

PIPENV\_IGNORE\_VIRTUALENVS=1 to force pipenv to ignore that environment and create  its own instead.

You can set PIPENV\_VERBOSITY=-1 to suppress this warning.



\=== TO-DO CLI Application ===

1\. Manage Users

2\. Manage Categories

3\. Manage Tasks

4\. Exit
