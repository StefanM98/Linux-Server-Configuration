# Linux-Server-Configuration
# Server Details

Public IP address: 18.217.11.75
SSH Port: 2200
URL: http://ec2-18-217-11-75.us-east-2.compute.amazonaws.com/

# Configuration Changes
- Added new 'grader' user
- Added grader to sudo group
- Updated all currently installed packages
- Setup SSH keys for grader
- Disabled root login
- Changed timezone to UTC
- Changed SSH port from 22 to 2200
- Configured Uncomplicated Firewall (UFW) to only allow connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
- Installed Apache to serve a python mod_wsgi app
- Installed PostgreSQL
- Added PostgreSQL user called catalog
- Installed Flask, SQLAlchemy, pip, oauth2client, requests, and httplib2
- Installed Git version control
- Cloned Catalog app repository
- Updated catalog.wsgi file 
- Updated Google OAuth client secrets file
- Updated Facebook OAuth client secrets file
- Configured Apache2 to serve the app
