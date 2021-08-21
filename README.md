# Django authentication boilerplate


This is Python/Django boilerplate for initial setup/authentication. I made this boilerplate to speed up initial setup.


### How to use this boilerplate?
- Install all the dependency, by using command: ```pip install -r requirements.txt```.
- Once that's done, go ahead and create a file named ```.env```, where you will put your SECRET_KEY and other virtual environments.
- Now, make migrations by typing command: ```python manage.py makemigrations```.
- Now that migrations are made it's time to migrate those changes to the database(for now we will be using sqlite3) by using command: ```python manage.py migrate```.
- You are all set! Now run the server by using command ```python manage.py runserver``` and go to the [this url to see you web page](http://127.0.0.1:8000).


If you find this helpful, please star the repo :)