# PHP School Website with CMS

A sample website for schools and colleges, with a simple PHP and MySQL CMS behind it.

## Screenshot

_Screenshot coming soon._

## Features

- Public pages: home, about, history, mission and contact
- User sign-up
- Admin page to add, update, view and delete records in the `studentwing` table

> **Note:** this is a student project and isn't hardened for production use (no prepared statements or password hashing).

## Tech stack

PHP (mysqli), MySQL, HTML, CSS, JavaScript

## Getting started

1. Install a local PHP and MySQL server, such as XAMPP.
2. Create a database called `dcs`.
3. Check the database settings in `connection.php`. The defaults are host `localhost`, user `root` and an empty password.
4. Put the project folder in your web root (for example `htdocs/`) and open `http://localhost/php-school-website-cms/`.

> TODO: the repo has no `.sql` file, so the tables (`studentwing`, `user`) must be created by hand.

## Project structure

```
index.php, main.html, about.html, history.html, mission.html, contact.html   Public pages
admin.html, insert.php, update.php, delete.php, view.php                     CMS
signup.html, signup.php                                                      Sign-up
connection.php, linker.php                                                   Database connection
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
