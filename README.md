Item Catalog Project by Dasheng Chen

Files:
finalproject.py -- python script with flask main application
itemcatalog.db -- sqlite database for item catalog
database_setup.py -- pathon script for sqlalchemy database schema
static/style.css -- css style for all views
templates/main.html -- main template for all pages
templates/newitem.html -- template for item add view
templates/catalog.html -- template for catalog and category overview for logined users
templates/publiccatalog.html -- template for catalog and category overview for public users
templates/deleteitem.html -- template for item delete view
templates/edititem.html -- template for item edit view
templates/item.html -- template for item view
templates/header.html -- header for all views
templates/footer.html -- footer for all views

Requirements:
Python
flask
sqlalchemy
SeaSurf

How to Run
1. Install VirtualBox and Vagrant
2. Download the project and unzip it into vagrant/project
3. Open a terminal window and input "vagrant up"
4. Sign into vagrant via inputing "vagrant ssh"
5. Change the directory to vagrant/tournament using "cd vagrant/project"
6. Run the test by inputting "python finalproject.py" in terminal
7. Open http://localhost:5000 in your browser