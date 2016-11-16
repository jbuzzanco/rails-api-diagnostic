# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
to keep the data safe(er) and more secure and to access it for separation of concerns from the front end.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
the model
```

Which layer in the MVC pattern communicates with the model?

```bash
the controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
they only copy back to the user what the controller gives them
```

What does C.R.U.D stand for?

```bash
create
read
update
destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
the model
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
def create
def read
def update
def destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
controller gets request, gives to model

model processes request with corresponding data, give data to controller

model gives data to server

server gives corresponding http response to user
```

What is the command to generate a new rails-api app?

```bash
rails generate
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
bundle exec rails drop:db
bundle exec rails create:db
bundle exec rails migrate:db
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
pet> rails   generate   scaffold   Items   name:string age:integer
```
