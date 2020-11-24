To start server:

1. In your terminal, type "cd server" to enter the correct directory to get this to work.

2. Enter pypi environment by typing "pipenv shell"

   - please install all necessary dependencies.
     - In your terminal, type "pipenv install"
     - Press "Enter/Return" to install all dependencies listed in Pipfile. Continue to the next step.

3. Enter a python repl by typing "python" in your terminal.

4. Once you see ">>>" type "from app import db"

5. Next command is "db.create_all()". If you don't get an error, you should get a new repl line back, and an app.sqlite file should appear in your folder.

6. Exit the repl with Ctrl/Cmd + Z

7. Once successful, you can enter the server by running the file. In your terminal, type "python app.py"

# Routes

> By using an API client platform such as Postman, you can test all routes by using the 'POST', 'GET', 'PATCH' and 'DELETE' commands.

> USE THE FOLLOWING SET-UP WHEN POPULATING API

- Method: POST
  URL: http://localhost:5000/add-book
  Content-Type: json
  Body: {
  "title": "test 1",
  "author": "test 1",
  "url": "test 1",
  "genre": "test 1",
  "star_rating": "1",
  "book_read": false
  }

- Method: GET
  URL: http://localhost:5000/books
  Content-Type: json

  - Lists each posted item in an array

- Method: PATCH
  URL: http://localhost:5000/book-read/<id>
  Content-Type: json
  Body: {
  "book_read": true
  }

  - target the desired id. id will be found in each item

- Method: DELETE
  URL: http://localhost:5000/delete-book/<id>
  - deletes desired item by id
