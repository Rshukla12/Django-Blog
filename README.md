# Django-Blog
### [https://micro-blogging-webapp.herokuapp.com/](https://micro-blogging-webapp.herokuapp.com/) [![Website micro-blogging-webapp.herokuapp.com](https://img.shields.io/website-up-down-green-red/http/micro-blogging-webapp.herokuapp.com.svg)](https://micro-blogging-webapp.herokuapp.com/)


This is an online blog website project, developed using Python's web framework Django.
For front-end designing I have used Twitter's front-end library Bootstrap4.
It is hosted on Heroku and Media is delivered through Cloudinary

## Screenshots
![](https://imgur.com/rVmRkpA.jpg)
![](https://imgur.com/tHUEhPk.jpg)
![](https://imgur.com/1TSciIF.jpg)
![](https://imgur.com/pOZpmBM.jpg)
![](https://imgur.com/DCdUxcv.jpg)


### Getting started
                
1. Install `git`,`python3`, `pip3`, `virtualenv` in your operating system
2. Create a development environment ready by using these commands
```
git clone https://github.com/Rshukla12/Django-Blog.git    # clone the project
cd Blog/blog		                                          # go to the project DIR
virtualenv -p python3 .venv		                            # Create virtualenv named .venv
source .venv/bin/activate		                              # Active virtualenv named .venv
pip install -r requirements.txt		                        # Install project requirements in .venv
python manage.py makemigrations		                        # Create migrations files
python manage.py migrate		                              # Create database tables
python manage.py collectstatic		                        # Create statics files
python manage.py runserver		                            # Run the project
```
3. Go to  `http://127.0.0.1:8000/` to use project

