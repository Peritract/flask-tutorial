# Flask App

Following the [Flask mega tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) in an attempt to learn Flask.

### Installation

1. Create and activate a virtual environment:

```
$ python venv venv

$ source ./venv/bin/activate
```

2. Install the necessary Python packages:

`$ pip install -r requirements.txt`

3. Create a `.env` file with the following properties:

```
SECRET_KEY=
```

### Development

To run a local development server, use the following command:

`$ flask run`

To run a shell within the app's context, use

`$ flask shell`

### Database

Currently this uses a SQLite database.

In order to update the database models/schema, run

`$ flask db migrate` followed by `$ flask db upgrade`