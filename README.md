Description of Project
This project is to create a basic clone of the AirBnB web app. It is divided into sections
1. The console
.Creating the data model
.Managing (create, update, destroy, etc) objects via a console / command interpreter
.Storing and persist objects to a file (JSON file)

2. Web static
.creating the HTML of your application
.creating template of each object

3. MySQL storage
.Replacing the file storage by a Database storage
.Maping the models to a table in database by using an O.R.M.

4. Web framework - templating
.Creating the first web server in Python
.Making the static HTML file dynamic by using objects stored in a file or database

5. RESTful API
.Exposing all objects stored via a JSON web interface
.Manipulating objects via a RESTful API

6. Web dynamic
.Loading objects from the client side by using my own RESTful API



Description of the command interpreter
A CLI allows you to communicate with your computer by typing text commands. You enter a command, and the computer responds accordingly.

How to start command interpreter:
.Start by importing the Cmd module
  import cmd

How to use command interpreter:
.Create a class that inherits from cmd.Cmd. This class will contain your CLI's functionality.
e.g class MyCLI(cmd.Cmd):
    pass

.Each CLI command is defined as a method in your class.
e.g class MyCLI(cmd.Cmd):
    def do_hello(self, line):
        """Print a greeting."""
        print("Hello, World!")

    def do_quit(self, line):
        """Exit the CLI."""
        return True

.To start your CLI, create an instance of your class and call cmdloop():
e.g if __name__ == '__main__':
    MyCLI().cmdloop()


