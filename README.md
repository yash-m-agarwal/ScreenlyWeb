# Installation and Usage

- Clone the Repo :
```
	git clone https://github.com/yash-m-agarwal/ScreenlyWeb
```

- Start a virtualenv
```
	virtualenv -p python3 Env
	source Env/bin/activate
```

- Installing Django
```
	pip install Django
``` 

- change dir into the folder named landingPage and be in the directory where `manage.py` file is located.

- Make migrations and start the server
```
	python manage.py makemigrations
	python manage.py migrate
	python manage.py runserver
```

- The above steps start the local server on localhost:8000
- Go to `http://127.0.0.1:8000/accounts/login/` in your browser. A login page will be displayed with asking for `Username` and `Password` as credentials.-
- On login it will re-direct the page to Screenly OSE which is hosted in Raspberry pi at ip address : `192.168.1.5`
- For more information on Screenly OSE go to [Screenly OSE](https://www.screenly.io/ose/ "Screenly")

# Live site

- Demo site is currently hosted on [Screenlylogin](http://yasha786.pythonanywhere.com/accounts/login/ "Login")

# Reference used

- Mozilla Official Docs
- pythonanywhere

# Author

- Yash M Agarwal