1. A user should be able to sign up and get logged in automatically 
2. A user should be able to log in / log out
3. A user should be able to add books to their list
4. A user should be able to edit/read/delete a book 
5. A user should be able to track their book status either reading, read, wishlist.

Model associations

A user has many books and a book has many users(many to many relationship)

Controller actions for books
index,show,new, create, edit,  update,destroy

controller actions for users
new, create, edit, update, destroy

create user migration
create books migration
create books user migration