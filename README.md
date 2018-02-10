# Udacity-Linux-Server-Configuration
This is the final project for the Udacity FullStack Web Development Nanodegree.

#### Project Description

Taking a baseline installation of a Linux server and preparing it to host The [https://github.com/AhmedElkashef02/Item-Catalogue](Item Catalogue) application. Also securing the server from a number of attack vectors, and installing and configuring a database server.

### Important Info

- IP Address: 18.194.244.229
- SSH Port: 2200
- Project URL: http://18.194.244.229

### Summary of configurations and software Installed

- Created user `grader` with sudo access and key-pair login.
- Login to user `grader` using the command `ssh grader@18.194.244.229 -p 2200 -i ~/.ssh/id_rsa`.
- Updated packages using `sudo apt-get update` & `sudo apt-get upgrade`.
- Configured Uncomplicated FireWall `UFW` to only allow ports `SSH`, `HTTP`, `NTP`.
- Configured the timezone to be UTC.
- Installed `Apache2`,`mod_wsgi`,`postgresql`,`Flask`,`httplib2`, `oauth2client`, `sqlalchemy`, `psycopg2`, `sqlalchemy_utils`.
- Renamed the main project file to `__init__.py` so it can be recognized by python as a package.
- Created a postgresql User `catalog` with limited permissions.
- Successfully cloned and deployed the Item Catalogue App.
