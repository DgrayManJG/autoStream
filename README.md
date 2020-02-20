autoStream

Personnal projet in python with framework django

utils link :

https://docs.djangoproject.com/fr/1.11/intro/tutorial01/

https://tutorial.djangogirls.org/fr/deploy/
https://tutorial-extensions.djangogirls.org/en/

http://www.seleniumhq.org/
web scraping
jenkins
rutube


PUSH ON GIT
	$ git status
	$ git add --all .
	$ git status
	$ git commit -m "message"
	$ git push

UPDATE site en prod

	$ cd ~/autoStream
	$ source myvenv/bin/activate
	(myvenv)$ git pull
	(myvenv)$ python manage.py collectstatic
