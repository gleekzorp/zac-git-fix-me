To start server:

1. In your terminal, type "cd server" to enter the correct directory to get this to work.

2. Enter pypi environment by typing "pipenv shell"

   - please install all necessary dependencies.
     - In your terminal, type "pipenv " then type the following (you can do this command all on one line):
       - flask
       - flask-marshmallow
       - flask-sqlalchemy
       - marshmallow-sqlalchemy
       - flask-cors
     - Press "Enter/Return" once all are listed to install all dependencies. Once the install is complete, proceed to the next step.

3. Enter a python repl by typing "python" in your terminal.

4. Once you see ">>>" type "from app import db"

5. Next command is "db.create_all()". If you don't get an error, you should get a new repl line back.

6. Exit the repl with Ctrl/Cmd + Z

7. Once successful, you can enter the server by running the file. In your terminal, type "python app.py"
