# BLOGR - ALTSCHOOL SECOND SEMESTER PROJECT

This is project was built with django and sqlite

### How to Run

- clone the project

```bash
git clone git@github.com:Mykell404/Altschool-Blogr.git
```

- Change to the project directory

```bash
cd Altschool-Blogr
```

- Create a virtual environment

```bash
python3 -m venv venv
```

- Start the virtual environment

```bash
. venv/bin/activate
```

- Install the depedencies

```bash
pip install -r requirements.txt
```

- Initialize the database

```bash
flask --app blog init-db
```

- Start the app

```bash
flask --app blog --debug run
```

The application should start running on Port 5000
