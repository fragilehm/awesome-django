<div align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat.svg" /></a>
  <br /><br />
  <img width="400" src="django-logo.svg" alt="Django logo">
</div>

# Awesome Django

> A curated list of awesome things related to Django.

## Contents

* [Resources](#resources)
  * [Official Resources](#official-resources)
  * [External Resources](#external-resources)
  * [Community](#community)
  * [Conferences](#conferences)
  * [Meetups](#meetups)
  * [Podcasts](#podcasts)
  * [YouTube Channels](#youtube-channels)
* [Third-Party Packages](#third-party-packages)
* [Tutorials](#tutorials)
  * [Beginner](#beginner-tutorials)
  * [Intermediate/Advanced](#intermediate-advanced)
  * [Docker](#docker)
* [Boilerplate](#boilerplate)
* [Open Source Apps](#open-source-apps)
* [Open Source Projects](#open-source-projects)
* [Django REST Framework](#django-rest-framework)
  * [Resources](#drf-resources)
  * [Tutorials](#drf-tutorials)
  * [DRF Boilerplate](#drf-boilerplate)
  * [Open Source Apps](#drf-open-source-apps)
* [Books and Courses](#books-and-courses)
* [Videos](#videos)
  - [Free](#free)
  - [Paid](#paid)

## Resources

### Official Resources

* [Django Official Website](https://www.djangoproject.com/)
* [Django Documentation](https://docs.djangoproject.com/en/dev/)
* [Django Polls Tutorial](https://docs.djangoproject.com/en/dev/intro/tutorial01/)
* [Django Source Code](https://github.com/django/django)

### External Resources

* [Django Packages](https://djangopackages.org/) - Comprehensive directory of reusable Django apps and tools.
* [Classy Class-Based Views](http://ccbv.co.uk/) - Detailed descriptions for each generic class-based view.
* [Django Sites](https://www.djangosites.org/) - Comprehensive listing of sites built with Django.
* [Pony Checkup](https://www.ponycheckup.com/) - Security checkups for Django sites.
* [Django Hunter](https://github.com/6IX7ine/djangohunter) - Tool to help identify incorrectly configured Django applications that are exposing sensitive information.
* [William Vincent's Website](https://wsvincent.com) - Up-to-date tutorials on Django and Django REST Framework.
* [Simple is Better than Complex](https://simpleisbetterthancomplex.com/) - Regularly updated website with many tutorials and tips on Django.
* [Full Stack Python's Django Page](https://www.fullstackpython.com/django.html) - Explanation of Django philosophy and links to other resources and tutorials.
* [RealPython](https://realpython.com/tutorials/django/)
* [TestDriven](https://testdriven.io/blog/)


### Community
* [Django Users Google Group](https://groups.google.com/forum/#!forum/django-users) - Very active discussion board for questions/answers.
* [Django Developers Google Group](https://groups.google.com/forum/#!forum/django-developers) - For contributions to Django itself only.
* Django IRC Channel - Chat with other Django users at irc://irc.freenode.net/django
* [Twitter](https://twitter.com/djangoproject) - For official announcements on updates, security fixes, etc.

### Conferences
* [DjangoCon US](https://2019.djangocon.us/)
* [DjangoCon Europe](https://2019.djangocon.eu/)
* [DjangoCon Australia](https://2018.djangocon.com.au/)
* [PyCon US](https://us.pycon.org/2019/)
* [Euro Python](https://ep2019.europython.eu/)
* [Complete listing of all PyCons globally](https://www.pycon.org/)

### Meetups
* [Meetups](https://www.meetup.com/topics/django/all/) - 400+ Meetup groups in 65 countries.

### Podcasts
* [TalkPython](https://talkpython.fm/)
* [Podcast Init](https://www.podcastinit.com/)

### YouTube Channels
* [DjangoCon US](https://www.youtube.com/channel/UC0yY6a79pPY9J0ShIHRf6yw)
* [DjangoCon Europe](https://www.youtube.com/user/djangoconeurope)
* [PyCon US](https://www.youtube.com/channel/UCsX05-2sVSH7Nx3zuk3NYuQ)
* [EuroPython](https://www.youtube.com/user/PythonItalia)
* [PyCon Australia](https://www.youtube.com/user/PyConAU)

## Third-Party Packages

> For a complete listing of all available packages, see [Django Packages](https://djangopackages.org/)

* [django-allauth](https://github.com/pennersr/django-allauth/) - User registration, social authentication, account management, and more.
* [django-compressor](https://github.com/django-compressor/django-compressor/) - Compress JavaScript/CSS into a single cached file
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms/) - DRY Django forms
* [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar/) - Configurable panels to debug requests/responses
* [django-environ](https://github.com/joke2k/django-environ) - Environment variables
* [django-extensions](https://github.com/django-extensions/django-extensions/) - Custom management extensions, notably `runserver_plus` and `shell_plus`
* [django-filter](https://github.com/carltongibson/django-filter) - Powerful filters based on Django QuerySets
* [django-guardian](https://github.com/django-guardian/django-guardian) - Per object permissions in Django
* [django-hijack](https://github.com/arteria/django-hijack) - Admins can log in and work on behalf of other users without having to know their credentials
* [django-model-utils](https://github.com/jazzband/django-model-utils) - Django model mixins and utilities
* [django-silk](https://github.com/jazzband/django-silk) - Live profiling and inspection of HTTP requests and database queries
* [django-storages](https://github.com/jschneier/django-storages) - A single library to support multiple custom storage backends for Django
* [django-tables2](https://github.com/jieter/django-tables2) - HTML tables with pagination/sorting
* [django-test-plus](https://github.com/revsys/django-test-plus/) - Useful additions to Django's default TestCase
* [easy-thumbnails](https://github.com/SmileyChris/easy-thumbnails) - Image thumbnails for Django
* [pytest-django](https://github.com/pytest-dev/pytest-django) - Use pytest features in Django
* [wagtail](https://github.com/wagtail/wagtail) - Popular Django content management system (CMS)
* [whitenoise](https://github.com/evansd/whitenoise) - Simplified static file serving for Python websites

> Django REST Framework specific packages

* [django-rest-auth](https://github.com/Tivix/django-rest-auth) - REST API endpoints for authentication and registration
* [django-rest-framework](https://github.com/encode/django-rest-framework) - Web APIs for Django
* [django-rest-framework-simplejwt](https://github.com/davesque/django-rest-framework-simplejwt) - JSON web tokens for DRF
* [django-rest-swagger](https://github.com/marcgibbons/django-rest-swagger) - API document generator for Swagger UI

## Tutorials

### Beginner Tutorials
* [Django Girls Tutorial](https://tutorial.djangogirls.org/en/) - Use function-based views to build a blog app.
* [Django for Beginners](https://djangoforbeginners.com/) - Use class-based views to build three apps of increasing complexity (part of a full-length book).
* [Mozilla Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) - Create a lending library app.
* [A Complete Beginner's Guide to Django](https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/) - In-depth and excellent walkthrough of a new Django app
* [Build a HackerNews clone](https://medium.com/@danieldng/a-little-hacker-news-in-django-part-1-f12aa81dc25d) - Very well-done tutorial for Django 2.0.

### Intermediate/Advanced Tutorials
* [Django Stripe Tutorial](https://testdriven.io/blog/django-stripe-tutorial/)
* [Setting up Stripe Connect with Django](https://testdriven.io/blog/setting-up-stripe-connect-with-django/)
* [Storing Django Static and Media Files on Amazon S3](https://testdriven.io/blog/storing-django-static-and-media-files-on-amazon-s3)

### Docker Tutorials
> Docker is commonly used to work with production-level databases locally like PostgreSQL or MySQL.

* [A Beginner's Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)
* [A Brief Intro to Docker for Djangonauts](https://www.revsys.com/tidbits/brief-intro-docker-djangonauts/)
* [How to use Django, Docker, and PostgreSQL](https://wsvincent.com/django-docker-postgresql/)
* [Docker for Django Developers (slides)](https://mherman.org/presentations/dockercon-2018/#1)
* [Dockerizing Django with Postgres, Gunicorn, and Nginx](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx)

## Boilerplate

* [cookiecutter-django](https://github.com/pydanny/cookiecutter-django) - A full-bodied starter project, highly customizable.
* [djangox](https://github.com/wsvincent/djangox) - A simpler approach with complete user authentication flow, Pipenv, and more.
* [django-starter-project](https://github.com/jpadilla/django-project-template) - A deliberately basic project that has multiple staging environments and Heroku deployment config.
* [docker-django](https://github.com/erroneousboat/docker-django) - A quick starter guide for Django and Docker together.

## Open Source Apps

* [Hello, World app](https://github.com/wsvincent/djangoforbeginners/tree/master/ch2-hello-world-app)
* [Message Board app](https://github.com/wsvincent/djangoforbeginners/tree/master/ch4-message-board-app)
* [Blog app with users and forms](https://github.com/wsvincent/djangoforbeginners/tree/master/ch7-blog-app-with-users)
* [Newspaper app with custom user model, full user auth](https://github.com/wsvincent/djangoforbeginners/tree/master/ch15-comments)
* [Behavior-Driven Development with Aloe](https://github.com/testdrivenio/django-aloe-bdd)
* [Image Sharing Blog](https://github.com/MeNsaaH/soMedia)

## Open Source Projects

* [wagtail](https://github.com/wagtail/wagtail) - Very popular Django-based content management system
* [Zulip](https://github.com/zulip/zulip) - Open-source team chat
* [django-oscar](https://github.com/django-oscar/django-oscar) - E-commerce for Django
* [django-cms](https://github.com/divio/django-cms) - CMS for Django
* [saleor](https://github.com/mirumee/saleor) - E-commerce storefront


## Django REST Framework

> The most popular way to build web APIs with Django.

### DRF Resources

* [Official Documentation](http://www.django-rest-framework.org/)
* [DRF Source Code](https://github.com/encode/django-rest-framework)
* [DRF](https://github.com/nioperas06/awesome-django-rest-framework)

### DRF Tutorials

* [Official REST Framework - A Beginner's Guide](https://wsvincent.com/official-django-rest-framework-tutorial-beginners-guide/)
* [DRF Blog API](https://wsvincent.com/django-rest-framework-tutorial/)
* [Building APIs with Django and DRF](https://books.agiliq.com/projects/django-api-polls-tutorial/en/latest/)
* [DRF Serializers, Viewsets, and Routers](https://wsvincent.com/django-rest-framework-serializers-viewsets-routers/)
* [DRF Todo API with User Auth](https://wsvincent.com/django-rest-framework-authentication-tutorial/)
* [DRF User Authentication](https://wsvincent.com/django-rest-framework-user-authentication-tutorial/)

> Tutorials using React front-end.

* [DRF with React: Todo API](https://wsvincent.com/django-rest-framework-react-tutorial/)
* [DRF with React](https://www.valentinog.com/blog/tutorial-api-django-rest-react/)
* [Making React and Django play well together](https://fractalideas.com/blog/making-react-and-django-play-well-together/)

### DRF Boilerplate

* [DRFx](https://github.com/wsvincent/drfx)

### DRF Open Source Apps

* [DRF Polls](https://github.com/wsvincent/drf-polls) - API of the official Django polls tutorial
* [DRF Blog](https://github.com/wsvincent/drf-blog-api) - Basic Blog API
* [ECGC](https://github.com/flowerncsu/ecgc-2017) - Example from DjangoCon 2017 talk [Write an API for Almost Anything](https://www.youtube.com/watch?v=-6tR5TffP0w)

## Books and Courses

> Django 2.1

* [Django for Beginners: Build websites with Python and Django](https://djangoforbeginners.com/)
* [REST APIs with Django: Build web APIs with Python and Django](https://restapiswithdjango.com/)
* [Build Your First Website with Django 2.1](https://transactions.sendowl.com/stores/9897/130290)
* [Develop a Real-Time Taxi App with Django Channels and Angular](https://testdriven.io/courses/real-time-app-with-django-channels-and-angular/?source=e4245ba649f3)
* [Practical Django 2 and Channels 2](https://www.amazon.com/dp/1484240987/?tag=wsvincent-20)
* [Django 2 Web Development Cookbook](https://www.amazon.com/dp/1788837681/?tag=wsvincent-20)

> Django 2.0

* [Hello Web App 2.0](https://hellowebbooks.com/learn-django/)
* [Django Design Patterns and Best Practices](https://www.amazon.com/dp/1788831349/?tag=wsvincent-20)
* [Django 2 by Example](https://www.amazon.com/dp/1788472489/?tag=wsvincent-20)

> Django 1.11

* [Two Scoops of Django: Best Practices for Django 1.11](https://www.amazon.com/dp/0692915729/?tag=wsvincent-20)
* [Test-Driven Development with Python](https://www.amazon.com/dp/1491958707/?tag=wsvincent-20)
* [Django RESTful Web Services](https://www.amazon.com/dp/1788833929/?tag=wsvincent-20)
* [Beginning Django](https://www.amazon.com/dp/1484227867/?tag=wsvincent-20)

## Videos

### Free

> Django 2.1

* [Django Authentication Tutorial by Vitor Freitas](https://youtu.be/60GTvKCuam8?list=PLLxk3TkuAYnryu1lEcFaBr358IynT7l7H)
* [Build a Startup with Django by CSDojo](https://youtu.be/UyQn0BhVqNU)
* [Just Django](https://www.youtube.com/channel/UCRM1gWNTDx0SHIqUJygD-kQ)

> Django 2.0

* [Build a Guestbook (30-part series) by Pretty Printed](https://www.youtube.com/watch?v=QVX-etwgvJ8&list=PLXmMXHVSvS-DQfOsQdXkzEZyD0Vei7PKf)
* [Blog Tutorial by Corey Schafer](https://youtu.be/UmljXZIypDc?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p)
* [CS50's Web Programming with Python and JavaScript](https://www.youtube.com/playlist?list=PLhQjrBD2T382hIW-IsOVuXP1uMzEvmcE5)

> Django 1.11

* [Todo App by Traversy Media](https://youtu.be/2yXfUPwlZTw)
* [Django Crash Course by Traversy Media](https://youtu.be/D6esTdOLXh4)

### Paid

> Django 2.1

* [Build Your First Website with Django](https://academy.masteringdjango.com/courses/build-your-first-website-with-django-2?ref=3474fd)

* [Build Backend Web Apps and APIs with Django](https://www.oreilly.com/library/view/web-development-in/9780134659824/)

* [Build a Real Estate App](https://click.linksynergy.com/link?id=1*FmkJFU6n4&offerid=507388.1952540&type=2&murl=https%3A%2F%2Fwww.udemy.com%2Fpython-django-dev-to-deployment%2F)

* [Ulimate Web Development Bootcamp](https://click.linksynergy.com/link?id=1*FmkJFU6n4&offerid=507388.1562632&type=2&murl=https%3A%2F%2Fwww.udemy.com%2Fthe-ultimate-beginners-guide-to-django-django-2-python-web-dev-website%2F)

> Django 1.11

* [Build a Django eCommerce Application](https://click.linksynergy.com/link?id=1*FmkJFU6n4&offerid=507388.1396598&type=2&murl=https%3A%2F%2Fwww.udemy.com%2Fpython-ecommerce-build-a-django-ecommerce-web-application%2F)

---

> Some links contain affiliate codes which help me justify the time to keep this list up-to-date.

### License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
