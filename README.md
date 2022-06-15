### Step 1: virtual environment

```sh
python3 -m venv env
. env/bin/activate
pip3 install -r requirments.txt
```

### Step 2: Setting up environment variables

Make a .env file in your root directory(Where manage.py resides)
```sh
touch .env #Creating .env file
```

Go to .env.example file to see how to set up .env file
Go to https://djecrety.ir/ generate a key and paste it in place of YOUR-SECRET-KEY in .env file

### Step 3: Running the server

```sh
python manage.py runserver #run the server
```

### Project
some imp commands
```sh
python manage.py runserver
python manage.py makemigrations
python manage.py migrate
```

## GIT
```sh
git init
git commit
git remote add origin git@github.com:durba-s/webbApp
git push -u origin master
```