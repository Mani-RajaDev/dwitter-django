# Dwitter Part 1: User and Profile Models

In this part of the development process, I set up the Django project, created an app called "dwitter", a user model, a profile model that allows users to follow other users.

## Steps

1. Created a new directory for the project and set up a virtual environment using `venv`.
2. Installed Django using `pip`.
3. Created a new project using the `django-admin startproject` command.
4. Created a new app within the project called "dwitter" using the `python manage.py startapp dwitter` command.
5. Unregistered the built-in User model and registered a new minimal User model with only the username field using the admin.py file for easy development and testing.
6. Created a new model called Profile in the models.py file with a OneToOne field that connects to the built-in User model and a follows field that is a ManyToMany field to self.
7. Modified the models.py file to include signals that automatically create a user profile when a user is created and make the user follow themselves.
8. Registered the profile model in the admin.py file.

## Next Steps
In Part 2 of this project, we will be adding CSS styles to our Django app using the Bulma framework. The Bulma framework is a popular CSS framework that provides a clean and modern design.
