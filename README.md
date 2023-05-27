# convin-assignment
A rest API built in Django to access Google calendar using OAuth 2.0

## Prerequisites
- Python 3.x
- Django 3.x
- Google developer console account
- A google calendar

## Running the project
1. Clone the repository.
2. Install pipenv and create a new django project in a virtual environment.

3. Install the dependencies

4. Create a project in the Google developer console and enable the Google Calendar API.

5. In the developer console, navigate to the Credentials page, create a new OAuth client ID, and specify authorized redirect URIs.

6. Set the client_id, client_secret, and redirect_uri in the settings.py file.

7. Set the url for the views in your urls.py file.

8. Start the development server python3 manage.py runserver
