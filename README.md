# Introduction #

For this project, I configured a base Ubuntu server and deployed a Flask
application to the server.

## Project URL: 52.43.135.40
## SSH Port: 2200

# Software Installed #

* Postgresql
* Python 2.7
* Flask
* SQLAlchemy

# Server Configuration Changes #

* Created a new user account (grader) wtih sudo permission
* Changed SSH port from 22 to 2200
* Configured firewall to only allow SSH (Port 2200), HTTP (Port 80), and
NTP (Port 123)
* Changed local timezone to UTC
* Disabled remote login and enforced key-based authentication
* Disabled remote logins for Postgresql

# Third-Party Resources Used #

* http://flask.pocoo.org/docs/1.0/
* http://www.postgresqltutorial.com/
* https://www.phusionpassenger.com/library/walkthroughs/deploy/python/ownserver/apache/oss/bionic/deploy_app.html#configuring-apache-and-passenger
