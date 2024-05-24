# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
https://github.com/Raja-Ramees/django-notes-app.git


2. Build the app
docker build -t notes-app .

3. Run the app
docker run -d -p 8000:8000 notes-app:latest

## Nginx

Install Nginx reverse proxy to make this application available 

```bash
sudo apt-get update
sudo apt install nginx

### Push Local Repository to GitHub:

Once you've created the repository, push your local project to GitHub:

```bash
git remote add origin https://github.com/Raja-Ramees/django-notes-app.git
git branch -M main
git push -u origin main

