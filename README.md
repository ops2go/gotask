# GoTask
by: Coleman Word

## Design
Code available in main.go

/add/           POST    Add a New Task

/               GET     Get Tasks

/complete/      GET     Show Pending Tasks

/deleted/       GET     Show Deleted Tasks

/edit/<id>      POST    Edit Post

/edit/<id>      GET     Show Edit Page

/trash/<id>     POST    Send to Trash

/delete/<id>    POST    Permenantly Delete   

/complete/<id>  POST    Complete Task

/login/         POST    Login

/login/         GET     Show Login Page

/logout/        POST    Logout

/restore/<id>   POST    Restore Task

/update/<id>    POST    Update Task

/change/        GET     Show Change Password

/register/      GET     Show Register Page

/register/      POST    Register in Database

```
go get -u \
    github.com/mattn/go-sqlite3     \
    github.com/gorilla/sessions     
```