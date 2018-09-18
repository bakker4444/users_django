# Coding Dojo Bootcamp Assignment
## Python, Django / Django / Users

### Assignment details

Create a new app called 'user_login'. Create a new model called 'User' that has the following fields/attributes



Please do the following

1. Create a new model called 'User' with the information above.
2. Successfully create and run the migration files
3. Using the shell...
    1. Know how to retrieve all users.
    2. Know how to get the last user.
    3. Create a few records in the users
    4. Know how to get the first user.
    5. Know how to get the users sorted by their first name (order by first_name DESC)
    6. Get the record of the user whose id is 3 and UPDATE the person's last_name to something else. Know how to do this directly in the console using .get and .save.
    7. Know how to delete a record of a user whose id is 4 (use something like User.objects.get(id=2).delete...).
4. (optional) Ninja:
    1. Find a way to validate the data coming in to the shell.  For example, make sure that "name" fields are a minimum length, "email" is a valid email, or that "email" doesn't already exist in the db.
