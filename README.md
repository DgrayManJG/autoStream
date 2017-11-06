autoStream

Personnal projet in python with framework django

utils link :

https://docs.djangoproject.com/fr/1.11/intro/tutorial01/

https://tutorial.djangogirls.org/fr/deploy/

Site de streaming automatiser

Idée générale : Faire un site de streaming automatiser avec du web scraping ou des appels
		a des api journalier ou par heure.
		Aucune source ne serai héberger sur notre site, seulement des appels a des 			
		platforme vidéo qui on une politique souple dans leur pays

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
