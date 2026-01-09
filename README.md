# Job Recruitment Portal

## Overview 📌
- In the event **Winter Of Code: Shadows Of Syntax** ❄️💻, I'll be learning about **Python** 🐍 based **framework named Django** 🌐.
- I will be pushing my learning progress according to **weekly tasks** 📅📚.

## Table Of Contents
- [Week-1](#week-1-%EF%B8%8F)
- [Week-2](#week-2-%EF%B8%8F)

## Week 1 🗓️
1. **Version Control (Git)** 🔧
   - [**Git**](https://git-scm.com/) 🔀 is used for version control to track and manage project changes.
   - Learned how to **add, commit, and push** a repository to GitHub ⬆️📦.
   - Created a .gitignore 🚫📁 file to exclude:
     - Virtual environment
     - Database files
     - Cache files
     - This ensures sensitive or unnecessary files are not publicly exposed.

2. **Python Virtual Environment** 🐍📦
   - A virtual environment is an isolated Python workspace for a project.
   - It prevents conflicts between dependencies of different projects ⚠️.
   - Created using:
     ````bash
     python -m venv venv
     ````
     (or `uv venv` using [uv](https://docs.astral.sh/uv/getting-started/installation/))
   - Activated using(for Windows Poweshell):
     ````bash
     .\venv\Scripts\Activate.ps1
     ````
   - Installed Django:
     ````bash
     pip install django
     ````
     (or `uv pip install django`)
   - Verified installation using:
     ````bash
     django-admin --version
     ````
   
4. **Creating and Running a Django Project** ▶️🖥️
   - Created a Django project using:
     ````bash
     django-admin startproject <project-name>
     ````
   - Project contains:
        - manage.py ⚙️
        - Main project folder with configuration files 📄.
        - All details about configuration files is given in its [official documentation](https://docs.djangoproject.com/en/6.0/intro/tutorial01/).
   - Go inside Project and ran the development server using:
     ````bash
     python manage.py runserver
     ````
   - Accessed the project at:
     ````bash
     http://127.0.0.1:8000/
     ````
   - In addition if localhost with port number 8000 is busy, then we can run this server in different port by adding different port number after `runserver` 🔄.
   - Successful setup displays the default Django Rocket Launch page 🚀🎉.

## Week-2 🗓️
