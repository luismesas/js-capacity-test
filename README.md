# Javascript Capacity Test

This is an application designed to test and prove a javascript developer capacities.

Use node.js to launch a local server. The application has several bugs in javascript code.

In order to complete the test, you must make a fork of this repository, and then submit a pull request with the code mistakes solved.

The time between the fork and the pull request, is going to be considered as well the solutions/fixes proposed.

Ofcourse you can cheat with times, but is up to you being honest with yourself.

Instructions:

- Install node.js ( http://nodejs.org/ )
- Install npm ( https://npmjs.org/ )
- Install connect node.js module ( *npm install connect* )
- Fork the project and clone it in your local git repository
- Launch the server *node todo-node.js* (it will start listening in localhost:8181 )
- Access in your favorite web browser to localhost:8181
- Fix the code errors
- Send a pull request with the code fixed.


These are the errors which make the application non functional:
- the application shows an error and doesn't display nothing :(
- adding a todo item causes an error to be shown in the console
- todo filter is not working :(
- destroying a todo causes an error to be shown in the console, and the todo doesn't disappear until the page get refreshed
- when you try to complete a task, it counts in the "items left" counter, but it doesn't get marked as completed
