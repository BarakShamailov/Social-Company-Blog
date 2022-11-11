# Social-Company-Blog
This project written in Python with Flask freamwork.

* The project is social company blog
* The company blog page allows users to create blog posts, edit existing posts, and delete them.
* Database managed by SQLAlchemy.

## How To Run ?
The first step is to install all the libraries from the requirements.txt file, by typing the following in the terminal:

```bash
   > pip3 freeze > requirements.txt
```

The second step is to connect to the database:

```bash
   > set FLASK_APP=app.py 
   > flask db init
   > flask db migrate -m "new tables"
   > flask db upgrade
```

The final step is to run:

```bash
   > python app.py
```
