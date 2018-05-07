## Introduction to Flask

#### [Mario Garcia](http://mattdark@github.io) · [@mariogmd](https://twitter.com/mariogmd)

---

## What is Flask?

----

### A microframework for web development in Python

---

## Requirements

----

- Python 2.7.x / Python 3.x
- pip<!-- .element: class="fragment" -->
- virtualenv<!-- .element: class="fragment" -->

----

### Installation

```
  python.org/downloads

```

----

#### Manjaro

```
  $ sudo pacman -S python3

```

----

### pip

```
  $ sudo pacman -S python-pip
```

----

### virtualenv

```
  $ sudo pip install virtualenv
```

----

```
  $ sudo pacman -S python-virtualenv
```

---

## Development tools

- Text editor
- Terminal<!-- .element: class="fragment" -->
- Git<!-- .element: class="fragment" -->
- GitHub / GitLab<!-- .element: class="fragment" -->

---

## Project

```
  $ mkdir myproject
  $ cd myproject
  $ virtualenv venv
```

----

```
 $ . venv/bin/activate
```

----

```
  $ pip install Flask
```

---

## Example

```
  #hello.py
  from flask import Flask

  app = Flask(__name__)

  @app.route("/")
  def hello():
    return "Hello world!"

  if __name__ == "__main__":
    app.run()
```

----

### Running

```
  $ export FLASK_APP = hello.py
  $ flask run
```

---

## Learn More

_[flask.pocoo.org](https//flask.pocoo.org)_

___

[@mariogmd](https://twitter.com/mariogmd)

mattdark@mozilla-mexico.org
