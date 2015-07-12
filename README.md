Atlantis College Website

Original HTML5 template designed by HTML5 UP (html5up.net)
Free for personal and commercial use under the CCA 3.0 license

Atlantis College is a big, modern, blocky affair with a mobile-style menu, fully responsive styling,
and an assortment of pre-styled elements.

- Built on Skel 3

- It uses flexbox*, which eliminates all kinds of terrible hacks and clunky layout
  stopgaps (like CSS grid systems).
* = not supported on IE8/9, but non-flexbox fallbacks are included

Icons: Font Awesome (fortawesome.github.com/Font-Awesome)
Other:
	HTML5 & CSS3
	jQuery
	html5shiv.js
	background-size polyfill (github.com/louisremi)
	Respond.js (j.mp/respondjs)
	Skel (skel.io)


GITHTUB

Atlantis College Website is available as a Github repository (https://github.com/martinzabek/atlantis-college)

Download: https://github.com/martinzabek/atlantis-college/archive/master.zip
Clone (HTTPS): https://github.com/martinzabek/atlantis-college.git
Clone (SSH): git@github.com:martinzabek/atlantis-college.git

To clone repository to your local machine:
- Open terminal and type "git clone git@github.com:martinzabek/atlantis-college.git" 
This will create a directory named "atlantis-college", initializes a .git directory inside it, pulls down all the data for that repository, and checks out a working copy of the latest version.
If you want to clone the repository into a directory named something other than "atlantis-college", you can specify that as the next command-line option:
- "git clone git@github.com:martinzabek/atlantis-college.git mydirectory"
That command does the same thing as the previous one, but the target directory is called "mydirectory"

WEBSITE STRUCTURE

<pre><code>
<em>root</em>
	&bull; <strong>assets</strong>
		&bull; <strong>css</strong>
			&bull; <strong>images</strong>
			&brvbar; font-awesome.min.css
			&brvbar; ie8.css
			&brvbar; ie9.css
			&brvbar; main.css
		&bull; <strong>js</strong>
			&bull; <strong>ie</strong>
				&brvbar; backgroundsize.min.htc
				&brvbar; html5shiv.js
				&brvbar; respond.min.js
			&brvbar; jquery.min.js
			&brvbar; jquery.scrollex.min.js
			&brvbar; jquery.scrolly.min.js
			&brvbar; main.js
			&brvbar; skel.min.js
			&brvbar; util.js
	&bull; <strong>courses</strong>
		&bull; <strong>administration</strong>
			&brvbar; index.html
		&bull; <strong>english-department</strong>
			&brvbar; index.html
		&bull; <strong>guidance</strong>
			&brvbar; index.html
		&bull; <strong>math</strong>
			&brvbar; index.html
		&bull; <strong>science</strong>
			&brvbar; index.html
		&bull; <strong>social-studies</strong>
			&brvbar; index.html
	&bull; <strong>images</strong>
	&brvbar; about.html
	&brvbar; <em style="color:#cd1c1f">app.yaml</em>
	&brvbar; apply.html
	&brvbar; browserconfig.xml
	&brvbar; contact.html
	&brvbar; courses.html
	&brvbar; index.html
	&brvbar; LICENSE
	&brvbar; links.html
	&brvbar; main.py
	&brvbar; manifest.json
	&brvbar; README.md
	&brvbar; robots.txt
	&brvbar; student-finance.html
	++ favicons
</code></pre>

References:
GIT Clone: https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository#Cloning-an-Existing-Repository
Creating new app with Google App Engine:
	https://developers.google.com/eclipse/docs/appengine
	https://cloud.google.com/appengine/docs
Hosting static website (Google App Engine):
	http://www.labnol.org/internet/host-website-on-google-app-engine/18801/
	http://www.hongkiat.com/blog/host-website-google-server/
Using static files (Google App Engine):
	https://cloud.google.com/appengine/docs/python/gettingstartedpython27/staticfiles