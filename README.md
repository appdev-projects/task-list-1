# Task List 1

Here is our target:

[https://task-list-1.herokuapp.com/](https://task-list-1.herokuapp.com/)

First, we can create a task table:

```
rails generate model task body:test user_id:integer complete:boolean
```

Then, a user table:

```
rails generate model user email:string username:string password_digest:string
```
