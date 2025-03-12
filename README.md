[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18572467)

# CSSE6400 Week 1 Practical

Construction of a simple HTTP server in Python.

Please see the [instructions](https://csse6400.uqcloud.net/practicals/week01.pdf) for more details.

Update this README file with appropriate information about your project,
including how to run it.

There are [resources](https://www.makeareadme.com) available to help you write a good README file.

# The Project - How to run the TODO App:

We have created a basic Flask app but how do we run it? When using poetry we need to run it in the following way:

> > poetry run flask --app todo run -p 6400

This command runs the flask –app todo run command inside the poetry environment with our dependencies installed.

In the endpoints.http file, a subtle "Send Request" should be visible between the comment and the GET. Click on this and a new tab should open up with the response from the API.
