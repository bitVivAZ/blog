---
layout: post
title: BitVivAZ DOTA STATS
description: DOTA 2 Stats Collecting Website
techstack: Made with Flask, Python, JavaScript, HTML, CSS, Bootstrap, Sqlite, Nginx, Gunicorn, AWS, GitPages, Figma
image: /personal/assets/webdev/dotastats/images/background.jpg
date: 2019-05-22 14:40:45
---

I created this project to learn more about using API's and serving data with a Flask application. It was also a good opportunity to learn more about AWS, therefore I decided to host the back end on an Amazon Elastic Compute Cloud.

Currently, the website only supports the resolution of 1920x1080.

<b>Website:</b> [BitVivAZ DOTA STATS](https://bitvivaz.com/dota-stats/)

### TODO

- Support more resolutions
- Add a search bar to filter through heroes

### Tech Stack

- Flask
- Python
- JavaScript
- HTML
- CSS
- Bootstrap
- SQLite
- Nginx
- Gunicorn
- Amazon Web Services
- GitPages
- Figma

### Features

- Heroes Pages, Data Page
- SQLite for database
- Python Script that retrieves data from Valve's DOTA API and stores it
- Flask Application which serves the SQLite data to the front-end website
- Front-end that parses all the data and displays it to the user
- Cronjob that runs a python script to update every hour all the data

### Source Code

- Front end: [GitHub](https://github.com/bitVivAZ/dota-stats)
- Back end: [GitHub](https://github.com/bitVivAZ/dota-stats-backend)

### Screenshots

<div class="box alt">
	<div class="row 50% uniform">
		<div class="u$"><span class="image fit"><img src="/personal/assets/webdev/dotastats/images/homepage.png" alt="homepage" /></span></div>
		<div class="6u"><span class="image fit"><img src="/personal/assets/webdev/dotastats/images/oracle.png" alt="oracle"/></span></div>
		<div class="6u"><span class="image fit"><img src="/personal/assets/webdev/dotastats/images/axe.png" alt="axe" /></span></div>
		<div class="u$"><span class="image fit"><img src="/personal/assets/webdev/dotastats/images/pudge.png" alt="pudge" /></span></div>
        <div class="6u"><span class="image fit"><img src="/personal/assets/webdev/dotastats/images/cm.png" alt="crystal maiden" /></span></div>
		<div class="6u"><span class="image fit"><img src="/personal/assets/webdev/dotastats/images/bane.png" alt="bane" /></span></div>
	</div>
</div>
