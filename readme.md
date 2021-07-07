# Welcome to AnimePiracy Project's GitHub repository!

## How to run development environment
Firstly, you must create the Python 3.8 supported virtual environment with `virtualenv` command at your terminal.
Then, you must activate it by using following commands:
 - Windows: `scripts\activate`
 - MacOS & Linux: `source scripts\activate`
Now, after all and your virtual environment is active, install project's PIP dependencies by following commands (note that on the macOS and Unix operating systems **you must write** `pip3` **instead of** `pip` like on Windows):

>     [macOS & Unix]
>     pip3 install -r requirements.txt
>     [Windows]
>     pip install -r requirements.txt
Now, you must run development server. To do that, just unarchive the animepiracy.zip archive, copy or move it to inside of your virtualenv's folder and type in to the terminal:

>     cd animepiracy
>     [macOS & Unix] python3 manage.py runserver
>     [Windows] python manage.py runserver
