AVS or Artist, Venue, Show
-----
### Introduction
This application provides an interface to store and update artist, venues, and shoes in a locally hosted database. It allows you to view,search,and store detailed information on these three lists.

This project was part of the Udacity FSND program. In it's current state `9b7163ca5740885675202f4dc975d6b65267b2cb` the project was reviewed and marked as meeting project rubric guidelines.

### Future Improvement Ideas
* I would like to implement form validation when submitting new artists, venues, and shows
* Make artists unavalaible to be added to a new show if already booked for a specific time slot

### Development Setup

First, [install Flask](http://flask.pocoo.org/docs/1.0/installation/#install-flask) if you haven't already.

  ```
  $ cd ~
  $ sudo pip3 install Flask
  ```

To start and run the local development server,

1. Initialize and activate a virtualenv:
  ```
  $ cd YOUR_PROJECT_DIRECTORY_PATH/
  $ virtualenv --no-site-packages env
  $ source env/bin/activate
  ```

2. Install the dependencies:
  ```
  $ pip install -r requirements.txt
  ```

3. Run the development server:
  ```
  $ export FLASK_APP=myapp
  $ export FLASK_ENV=development # enables debug mode
  $ python3 app.py
  ```

4. Navigate to Home page [http://localhost:5000](http://localhost:5000)
