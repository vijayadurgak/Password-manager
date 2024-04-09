<h1 align='center'>Password manager</h1>

---

<p align="center">
  A password manager to store multiple passwords for multiple users.
  All the passwords are encrypted before stored and a user cant access other users informations.
</p>

<p align="center">
	
  <a href="https://github.com/luis705">
    <img alt="Made by Luis Otávio" src="https://img.shields.io/badge/made%20by-Luís%20Otávio%20Amorim-brightgreen">
  </a>

  <img alt="Last Commit" src="https://img.shields.io/badge/last%20commit-june%202020-yellowgreen">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

---


# Table of Contents
<ul>
	<li><a href="#-getting-started">Getting Started</a></li>
	<li><a href="#-features">Features</a></li>
	<li><a href="#to-do">To do</a></li>
</ul>

---

# 🚀 Getting Started
<h2> Prerequisites </h2>

<h3>Clone</h3>
<ul>
	<li>Clone this repo using in the terminal:
</ul>

```
git clone git@github.com:luis705/password-manager.git
```
<h3>Install python</h3>
<ul>
	<li>Windows
		<p>Go to <a href="http://python.org/download">python.org</a>, download the installer and run it.</p>
	</li>
	<li>Linux
		<p>Type on terminal:</p>
	</li>
</ul>

```
sudo apt-get install python3
```

<h3>Install required packages</h3>
<p>Open the terminal and run</p>

```
pip install cryptography PyQt5
```


<h2>Using</h2>
<p>To use the manager just open the terminal and run main.py with</p>

```
python3 main.py
```
<p>In case you want to execute the GUI version run the file gui.py</p>

```
pythohn3 gui.py
```

---

# 📋 Features

- [X] Multiple users 
- [X] Passwords are stored encrypted with a diferent key for each user
- [X] Options to add or remove user
- [X] Options to add remove, update and check password for a given service
- [X] Option to check registered services
- [X] GUI

# To Do
- [ ] Avoid SQL injection attacks

<h2> Built with</h2>
<ul>
	<li>Core
    		<p>
			<a href="python.org">Python</a> - a easy to learn, but powerfull programming language
		</p>
  	</li>
  	<li>Storage
    	<p>
				<a href="https://www.sqlite.org">SQLite</a> -  
				a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
			</p>
  	</li>
		<li>GUI
			<p>
			<a href='https://www.riverbankcomputing.com/software/pyqt/'>PyQt5</a> - 
				Bidings for <a href='https://www.qt.io/'>the QtCompany's</a> Qt application framework implemented as python modules
			</p>
			
</ul>
	
--- 

# 📝 License </h1>

<img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

This project is licensed under the MIT license - see the <a href="https://github.com/luis705/password-manager/blob/master/LICENSE">LICENSE</a> file for details

