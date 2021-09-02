# Navycut - The Fullstack WebFramework

<p align="center">
  <a href="https://navycut.github.io"><img src="https://raw.githubusercontent.com/navycut/navycut/main/logos/navycut_logo.png" alt="FastAPI"></a>
</p>

## Overview
With Navycut, you can take Web applications from concept to launch in a matter of hours. Navycut takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.

### Why Navycut
Navycut provides the Flask based fullstack web development platform to create an interactive website instantly.

### Fullstack Support
Navycut has the Flask based backend system as well as the Jinja2 Based template rendering system to design the frontend.

### Ridiculously Fast
Navycut was designed to help developers take applications from concept to completion as quickly as possible.

### Fully Loaded
Navycut includes dozens of extras you can use to handle common Web development tasks. Navycut takes care of user authentication, content administration, site maps, RSS feeds, and many more tasks — right out of the box.

### Reassuringly Secure
Navycut takes security seriously and helps developers avoid many common security mistakes, such as SQL injection, cross-site scripting, cross-site request forgery and clickjacking. Its user authentication system provides a secure way to manage user accounts and passwords.

### Incredibly Versatile
Companies, organizations and governments have used Django to build all sorts of things — from content management systems to social networks to scientific computing platforms.

## Installation
Being a Python Web framework, Python requires Python. You must need to use Python version 3.6 or later. Python includes a lightweight database called SQLite so you won’t need to set up a database just yet. Get the latest version of Python at <a href="https://www.python.org/downloads/">https://www.python.org/downloads/</a> or with your operating system’s package manager. You can verify that Python is installed by typing python from your shell;
you should see something like:

```python
Python 3.x.y
[GCC 4.x] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
#### Install navycut from pypi using pip:
```bash
pip install -U navycut
```
#### Install navycut from source code:
```bash
git clone https://github.com/navycut/navycut.git
cd navycut
python setup.py install 
```
#### To verify that Navycut can be seen by Python, type python from your shell. Then at the Python prompt, try to import navycut:
```bash
>>> import navycut
>>> print(navycut.get_version())
0.0.4
```