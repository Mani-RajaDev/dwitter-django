# Part 3: Implementing Follows and Dweets
In this part of the development process,I added functionality that allows users to follow and unfollow other profiles, as well as created a backend logic for posting and displaying dweets on the user dashboard. This allows for a more engaging user experience, enabling users to easily connect with other users and share their thoughts through dweets.

## Steps
1. Added a follow and unfollow button below the user profile user name using HTML and CSS.
2. Updated the `profile` view function in views.py file to handle follow and unfollow requests. When a user clicks the follow button, the target user is added to the logged-in user's following list. When a user clicks the unfollow button, the target user is removed from the logged-in user's following list.
3. Created a Dweet model with a foreign key to the User model and a TextField for the dweet content.
4. Used the Django admin interface to add dweets to the database (will be going to implement dweet posting through the user dashboard).
5. In the user dashboard view, retrieved all the dweets from the users that the logged-in user is following and displayed them in the template.
6. Used HTML and CSS to format the dweets on the user dashboard page.

## Next Steps
In the fourth and final part of the development process, I will build upon the features implemented in Part 3 and add the ability for users to submit dweets through a Django form on the user dashboard. I will also add measures to prevent double submissions and handle any errors that may arise.
