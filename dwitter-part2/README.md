# Part 2: Designing Templates and Front-End Styling

In this part of the development process, I added a base template using Bulma CSS and implemented the ability to list all user profiles, access individual profile pages, and display the profiles a user follows and the profiles that follow the user.

## Steps

1. Created a new HTML base template (`base.html`) in the templates directory of the dwitter app.
2. Added the Bulma CSS stylesheet to the base template using a CDN link.
3. Created a new HTML template (`profile_list.html`) for the list of user profiles which inherits the base template.
4. Modified the views.py file to include a view function (`profile_list()`) that retrieves all user profiles and renders the user profile list template.
5. Added a URL route in urls.py to map to the view function.
6. Created another HTML template (`profile.html`) which also inherits the base template for the individual user profile pages.
7. Modified the views.py file to include a new view function (`profile()`) that retrieves an individual user profile and renders the user profile page template.
8. Added a new URL route in urls.py to map to the new view function.
9. Linked the profile pages by updating the links in the profile list to point to the correct user profile page.

## Next Steps
In the third part of the development process, I will be implementing the functionality for users to follow and unfollow other profiles, as well as creating the back-end logic for dweets. This will involve creating a new model to store dweets, and displaying dweets on the front-end. Stay tuned for more updates on this exciting development!
