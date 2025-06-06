## forum-advanced-features

### Objectives

You must follow the same [principles](../README.md) as the first subject.

In `forum advanced features`, you will have to implement the following features :

- You will have to create a way to notify users when their posts are :

  - liked/disliked
  - commented

- You have to create an activity page that tracks the user own activity. In other words, a page that :

  - Shows the user created posts
  - Shows where the user left a like or a dislike
  - Shows where and what the user has been commenting. For this, the comment will have to be shown, as well as the post commented

- You have to create a section where you will be able to Edit/Remove posts and comments.

We encourage you to add any other additional features that you find relevant.

### Instructions

- The backend must be written in **Go**
- The code must respect the [good practices](../../good-practices/README.md)
- It is recommended to have **test files** for [unit testing](https://go.dev/doc/tutorial/add-a-test).

### Allowed packages

- All [standard go](https://golang.org/pkg/) packages are allowed.
- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)
- [bcrypt](https://pkg.go.dev/golang.org/x/crypto/bcrypt)
- [gofrs/uuid](https://github.com/gofrs/uuid) or [google/uuid](https://github.com/google/uuid)

### This project will help you learn about:

- Real-time notifications
- Users activity tracking
