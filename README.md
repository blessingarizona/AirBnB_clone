Description of Project: <br />
This project is to create a basic clone of the AirBnB web app. It is divided into sections <br />
1. The console <br />
.Creating the data model <br />
.Managing (create, update, destroy, etc) objects via a console / command interpreter <br />
.Storing and persist objects to a file (JSON file) <br />

2. Web static <br />
.creating the HTML of your application <br />
.creating template of each object <br />

3. MySQL storage <br />
.Replacing the file storage by a Database storage <br />
.Maping the models to a table in database by using an O.R.M. <br />

4. Web framework - templating <br />
.Creating the first web server in Python <br />
.Making the static HTML file dynamic by using objects stored in a file or database <br />

5. RESTful API <br />
.Exposing all objects stored via a JSON web interface <br />
.Manipulating objects via a RESTful API <br />

6. Web dynamic <br />
.Loading objects from the client side by using my own RESTful API <br />

Description of the command interpreter <br />
A CLI allows you to communicate with your computer by typing text commands. You enter a command, and the computer responds accordingly. <br />

How to start command interpreter: <br />
.Start by importing the Cmd module <br />
  import cmd <br />

How to use command interpreter: <br />
.Create a class that inherits from cmd.Cmd. This class will contain your CLI's functionality. <br />
e.g class MyCLI(cmd.Cmd): <br />
    pass <br />

.Each CLI command is defined as a method in your class. <br />
e.g class MyCLI(cmd.Cmd): <br />
    def do_hello(self, line): <br />
        """Print a greeting.""" <br />
        print("Hello, World!") <br />

    def do_quit(self, line): 
        """Exit the CLI.""" 
        return True 

.To start your CLI, create an instance of your class and call cmdloop(): <br />
e.g if __name__ == '__main__': <br />
    MyCLI().cmdloop()


