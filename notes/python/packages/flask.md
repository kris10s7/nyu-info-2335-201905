# The `flask` Package

Reference:

  + [Website](http://flask.pocoo.org/)
  + [Docs](http://flask.pocoo.org/docs/1.0/)
  + [Source](https://github.com/pallets/flask)
  + [Quick-start Guide](http://flask.pocoo.org/docs/1.0/quickstart/)
  + [Tutorial](http://flask.pocoo.org/docs/1.0/tutorial/)

The `flask` package provides a micro-framework for making applications with web interfaces (a.k.a "web applications").

Run a `flask` application "in development" using a web server on your local machine, and/or "in production" using a remote web server hosted by a provider like Heroku. If you run it in development, you should be able to use it by visiting `localhost:5000` in a browser, whereas if you run it in production, you should be able to use it by visiting the production server's URL.

## Installation

First install `flask`, if necessary:

```sh
pip install flask
```

## Usage

Follow the [Official Flask Tutorial](http://flask.pocoo.org/docs/1.0/tutorial/).

Also reference these example applications by the professor and previous students:

App Name | Functionality Description
--- | ---
[Rock-Paper-Scissors (Flask)](https://github.com/prof-rossetti/rock-paper-scissors-flask) | Prompts the user to select an option from a dropdown menu, then processes that selection and displays the results on another page.
[Starter Web App](https://github.com/prof-rossetti/web-app-starter-flask) | A basic navigable web application with examples of capturing user inputs through a web form.
[Starter Web App w/ Google Sheets datastore](https://github.com/prof-rossetti/web-app-starter-flask-sheets) | A basic navigable web application with examples of reading and writing data to and from a Google Sheets datastore.
[DineCision](https://github.com/jessicalee127/DineCision) by @jessicalee | Prompts the user to input their zipcode via a web form so it can use the Yelp API to provide a dining recommendation.
[GMR's Algo Machine](https://github.com/s2t2/spotify_app/) by @gmr50 | Prompts the user to login to their Spotify account so it can create new Spotify playlist recommendations on their behalf.
[Products API](https://github.com/prof-rossetti/products-api-flask) | A JSON API with no front-end interface, uses CSV datastore.
[Salad System](https://github.com/prof-rossetti/salad-system-flask) | Includes a front-end interface and uses an SQL database as a datastore.
