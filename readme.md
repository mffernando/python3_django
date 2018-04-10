## Quick Installation Guide

Installing the Django Framework using Python3 on Ubuntu 16.04 (Xenial Xerus).

# Python Installation (as sudo user (root)):
sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install python3-pip build-essential libssl-dev libffi-dev python3-dev

# Django Installation:
pip3 install django

#Check Django version:
python3 -m django --version

#Create new project:
django-admin startproject project_name

#Run project:
cd project_name
python3 manage.py runserver
*ignore the warning 'python manage.py migrate' for now.*

#Test in the browser:
localhost:8000

If the message 'The install worked successfully! Congratulations!' django installation is ok.
