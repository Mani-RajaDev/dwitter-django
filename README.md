# dwitter-django

Welcome to my social network app, developed using Django! This app allows users to post text messages and follow other users, similar to Twitter.

## Overview

The development process is divided into four parts:

1. Setting up the Django project, extending the built-in user model, setting up the profile relationship model, and implementing a Post-Save Hook .
2. Adding CSS styles using the Bulma framework.
3. Building and handling post requests.
4. Building and submitting HTML forms with Django.

## Development Process

### Part 1: Setting up the Django Project

In the first part of the development process, I set up the Django project, extended the built-in user model, and set up the profile relationship model. Here are the steps I took:

- Created a new directory for the project and set up a virtual environment using `venv`.
- Installed Django using `pip`.
- Created a new project using the `django-admin startproject` command.
- Created a new app within the project called "dwitter" using the `python manage.py startapp dwitter` command.
- Extended the built-in user model.
- Set up the profile relationship model using `OnetoOneField` and `ManyToManyField`.
- Added the source code for this part to the `dwitter-part1` subdirectory.

## Conclusion

That's it for now! I'll continue to update this README.md file as I make progress on my social network app development project. Thank you for checking it out!
