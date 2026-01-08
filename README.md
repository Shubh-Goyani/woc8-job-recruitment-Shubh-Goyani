# Job Recruitment Portal (WOC)

## Overview
- In the event Winter Of Code: Shadows Of Syntax, I'll be learning about **Python** based **framework named Django**.
- So, I'll be pushing my work on learning Django according to the weekly tasks.



## Week 1:
1. **Version Control:**
   - Basically learned things required for **Version Control** which means **a system which helps to track changes made by me in my code over time**. And **Git** is the type of Version Control.
   - Installed [Git](https://git-scm.com/) and learned about what all needs to add, commit and push any repository to my GitHub account which stores all changes made by me.
   - Also made `.gitignore` file which is ignored while pushing my repository, it is important to made beacuse we doesn't want our **virtual environment, database and cache files** to be opened for everyone.
2. **Python Virtual Environment:**
   - It is a **Python workspace** where we can build our projects.
   - Without **virtual environment**, we can install libraries globally for all project which obviously doesn't make sense 'cause we want our project to be isolated.
   - With **virtual environment**, we'll have project specific python packages and versions.
   - `venv` is a built-in **Python module** to create virtual environment.
   - By command `python -m venv venv`, we can make virtual environment for our project. First `venv` is module and second `venv` is folder name.
   - Now we have to activate our **virtual environment** in order to use **Django** inside our project. It's command is `.\venv\Scripts\Activate.ps1`.
   -  Install **Django** using `pip install django`. And verify its version by `django-admin --verson`.
