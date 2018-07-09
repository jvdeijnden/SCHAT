# SCHAT
During the SCHAT project research was conducted on how the interface of a track &amp; trace system (a
system used to locate missing items) should be designed. This project was elaborated whilst using
the V-model. At first a study was conducted. The results of this study were used to create three
possible interfaces. These interfaces were then tested by nurses and caretakers from a single care
home. With the results from these tests, the interfaces were optimized after which a selection
procedure followed. During this procedure, the research team looked at which interface was tested
best: this turned out to be the interface with categories.

This prototype was focused on database management and search functionality for the interface.

# Dependencies
1. Django
2. django-countries
3. simplejson
4. spycopg2

# Installation
1. Install Python 3.6 and the listed dependencies
2. Install database software, preferably PostgreSQL
3. Download the source code from this repository
4. In settings.py (root folder), change the 'DATABASES' parameters to match your database
5. In the project root, run Python with the command "manage.py migrate" to setup the database for use with the webserver
6. Next, run "manage.py createsuperuser" and follow instructions to make an admin account for the Django admin interface
7. Finally, run "manage.py runserver 0:80" to run the webserver from your local machine on port 80
