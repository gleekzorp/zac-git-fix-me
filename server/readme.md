To start server:

1. In your terminal, type "cd server" to enter the correct directory to get this to work.

2. Enter pypi environment by typing "pipenv shell"

   - please install all necessary dependencies.
     - In your terminal, type "pipenv install"
     - Press "Enter/Return" to install all dependencies listed in Pipfile. Continue to the next step.

3. Enter a python repl by typing "python" in your terminal.

4. Once you see ">>>" type "from app import db"

5. Next command is "db.create_all()". If you don't get an error, you should get a new repl line back.

6. Exit the repl with Ctrl/Cmd + Z

7. Once successful, you can enter the server by running the file. In your terminal, type "python app.py"
