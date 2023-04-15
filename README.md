# dwitter-django

Welcome to my social network app, developed using Django! This app allows users to post text messages and follow other users, similar to Twitter.

## Overview

The development process is divided into four parts:

1. Creating User and Profile Models: Set up the base project, extend the Django user model, and implement a post-save hook.
2. Designing Templates and Front-End Styling: Design a visually appealing user interface by creating a base template with Bulma. Create a dynamic list of all user profiles and enable easy access to individual profile pages.
3. Implementing Follows and Dweets: Allow users to follow and unfollow other profiles, create the back-end logic for dweets (user posts), and display them on the front end.
4. Creating Forms and Handling Submissions: Enable users to submit dweets through a Django form, prevent double submissions, handle errors, and improve the front-end user experience.

## Development Process

### Part 1: User and Profile Models

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
