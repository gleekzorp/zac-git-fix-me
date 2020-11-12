# Bugs!!!!

> Please work through this project and help me fix all the nasty bugs.

> Please be kind to the next person and update the readme files. Such as how to get the python server up and running, how to get the database setup, what routes are available, how to get the react client started, ect.

> After you have fixed all the bugs and updated the readme files. Please try and make it your own. There is currently no styles, some of the api routes are not even being used and the clients folder has some horrible file organization.

# How To Start

- Instructions on how to contribute to this repo are below. For a full deep dive into how to contribute to open source, please refer to [THIS REPO](https://github.com/firstcontributions/first-contributions).

1. Fork the repo
2. Clone the repo
3. Create a branch
4. Make necessary changes and commit those changes
5. Push changes to GitHub
6. Submit your changes for review
7. Message me so I know you have made changes

# Zac's fixes

> version updated to 0.2.2

> Moved app.sqlite, package.json, Pipfile, .vscode and pycache to "server" directory

> Moved package-lock.json, Pipfile.lock and .env to "client" directory

> added .gitignore file, and marked .env, node_modules and "**pycache**" files to be ignored

> attached DOM element id "root" to index.js to compile on screen

> in books-list.js, changed initial state of books from "null" to and empty array []

> handleSubmit method in book-form "Add Book" attached with "DELETE" call which throws an error, replaced with "POST"

> syntax errors in app.py

    - (line 49) "titles" into "title"
    - (line 78) "bookread" into "book_read"

TO RUN SERVER:

- In your terminal, cd into "server" directory and type "pipenv shell".

- Then run python app.py. CTRL + click the link provided to open.

> Added 6 books to the list via the server using POST (Implemented by hard-coding in POSTMAN)

> Deleted 2 by id using DELETE. Made sure GET methods are running.

    - Currently id 1, 4, 5, 6 populate the list
    - id 1 edited to book_read: true
    - POST, GET, PATCH, and DELETE all operational
