# **djreset - Django Project Reset Tool**

`djreset` is a command-line interface (CLI) tool designed to help developers quickly reset their Django projects. It automates the process of:

- Deleting migration files (except `__init__.py` and `__pycache__`).
- Removing SQLite database files.
- Deleting the `media` directory.
- Re-running `makemigrations` and `migrate` commands.
- Creating a superuser with default credentials (`username=admin` and `password=admin`).
- Optionally, starting the Django development server.

This tool is perfect for quickly setting up a fresh environment or for resolving migration and database issues in Django projects.
