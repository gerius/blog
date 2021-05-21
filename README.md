# blog: Blog site

## task zuri training ( create a blog site witch django)

### link of demo: https://blogsiteweb.herokuapp.com/

### Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/gerius/blog.git
$ cd blog
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ pip install pipenv
$ pipenv shell
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `pipenv`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd blog
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/home/`.


**thank!!!**

