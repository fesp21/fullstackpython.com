title: Django
category: page
slug: django
sort-order: 0402
meta: Django is a widely used Python web framework with a 'batteries-included' philosophy. Learn more about Django on Full Stack Python.


# Django
[Django](http://www.djangoproject.com/) is a widely used Python web 
application framework with a "batteries-included" philosophy. The principle
behind batteries-included is that the common functionality for building
web applications should come with the framework instead of as separate
libraries. 


<a href="http://www.djangoproject.com/" style="border: none;"><img src="theme/img/django-logo-positive.png" width="100%" alt="Official Django logo. Trademark Django Software Foundation." class="technical-diagram" /></a>


For example, 
[authentication](https://docs.djangoproject.com/en/dev/topics/auth/),
[URL routing](https://docs.djangoproject.com/en/dev/topics/http/urls/), a 
[templating system](https://docs.djangoproject.com/en/dev/topics/templates/),
an [object-relational mapper](https://docs.djangoproject.com/en/dev/topics/db/),
and [database schema migrations](https://docs.djangoproject.com/en/dev/topics/migrations/)
(as of version 1.7) are all included with the [Django framework](https://pypi.python.org/pypi/Django/). 
Compare that included functionality to the Flask framework which requires a 
separate library such as 
[Flask-Login](https://flask-login.readthedocs.org/en/latest/)
to perform user authentication. 

The batteries-included and extensibility philosophies are simply two different
ways to tackle framework building. Neither philosophy is inherently better 
than the other.


## Why is Django a good web framework choice?
The Django project's stability, performance and community have grown 
tremendously over the past decade since the framework's creation. Detailed
tutorials and best practices are readily available on the web and in books.
The framework continues to add significant new functionality such as 
[database migrations](https://docs.djangoproject.com/en/dev/topics/migrations/)
with each release. 

I highly recommend the Django framework as a starting place for new Python web 
developers because the official documentation and tutorials are some of the 
best anywhere in software development. Many cities also have Django-specific
groups such as [Django District](http://www.meetup.com/django-district/),
[Django Boston](http://www.meetup.com/djangoboston/) and 
[San Francisco Django](http://www.meetup.com/The-San-Francisco-Django-Meetup-Group/) 
so new developers can get help when they are stuck.

There's some debate on whether 
[learning Python by using Django is a bad idea](http://www.jeffknupp.com/blog/2012/12/11/learning-python-via-django-considered-harmful/). 
However, that criticism is invalid if you take the time to learn the Python
syntax and language semantics first before diving into web development.


<div class="well see-also">
While you're learning about Django you should also read up on
<a href="/web-frameworks.html">web frameworks</a> and check out the
<a href="/bottle.html">Bottle framework</a>.
</div>


## Django tutorials
* [Test-Driven Development with Python](http://www.obeythetestinggoat.com/) 
  focuses on web development using Django and JavaScript. This book uses 
  the development of a website using the Django web framework as a real
  world example of how to perform test-driven development (TDD). There is
  also coverage of NoSQL, websockets and asynchronous responses. The book can
  be read online for free or purchased in hard copy via O'Reilly.

* [Tango with Django](http://www.tangowithdjango.com/book17/) is an extensive 
  set of free introductions to using the most popular Python web framework. 
  Several current developers said this book really helped them get over the 
  initial framework learning curve. It's recently been updated for Django 1.7!

* The [Django Girls Tutorial](http://tutorial.djangogirls.org/en/index.html)
  is a great tutorial that doesn't assume any prior knowledge of Python or
  Django while helping you build your first web application.

* [2 Scoops of Django](http://twoscoopspress.com/products/two-scoops-of-django-1-6) 
  by Daniel Greenfeld and Audrey Roy is well worth the price of admission if
  you're serious about learning how to correctly develop Django websites.

* [Effective Django](http://effectivedjango.com/) is another free introduction
  to the web framework.

* The [Django subreddit](http://www.reddit.com/r/django) often has links to
  the latest resources for learning Django and is also a good spot to ask 
  questions about it.

* Lincoln Loop wrote a 
  [Django Best Practices guide](http://lincolnloop.com/django-best-practices/)
  for the community.

* Steve Losh wrote an incredibly detailed [Django Advice guide](http://stevelosh.com/blog/2011/06/django-advice/).

* [Django by Example](http://lightbird.net/dbe2/) is a set of tutorials for
  creating Django projects such as a blog, forum, issue tracker and portfolio.
  This is a good site if you want to dive right into the code with minimal
  prose.

* [Lightweight Django](http://programming.oreilly.com/2014/04/simplifying-django.html)
  has several nice examples for breaking Django into smaller simplier 
  components.

* The [Definitive Guide to Django Deployment](https://github.com/rogueleaderr/definitive_guide_to_django_deployment)
  explains the architecture of the resulting set up and includes Chef scripts
  to automate the deployment.

* [Deploying a Django app on Amazon EC2 instance](http://agiliq.com/blog/2014/08/deploying-a-django-app-on-amazon-ec2-instance/)
  is a detailed walkthrough for deploying an example Django app to Amazon
  Web Services.

* This [step-by-step guide for Django](http://aliteralmind.wordpress.com/2014/09/21/jquery_django_tutorial/)
  shows how to transmit data via AJAX with JQuery.

* [Deploying Django on AWS](http://www.nickpolet.com/blog/deploying-django-on-aws/1/)
  is another walkthrough for deploying Django to AWS.

* [django-awesome](https://github.com/rosarior/awesome-django) is a curated
  list of Django libraries and resources.

* [Starting a Django Project](https://realpython.com/learn/start-django/) 
  answers the question, “How do I set up a Django (1.5, 1.6, or 1.7) project 
  from scratch?”

* The [recommended Django project layout](http://www.revsys.com/blog/2014/nov/21/recommended-django-project-layout/)
  is helpful for developers new to Django to understand how to structure
  the directories and files within apps for projects.

* The [Django Request-Response Cycle](http://irisbeta.com/article/245366784/the-django-request-response-cycle/)
  explains what happens when you visit a webpage generated by Django.

* This [Python Social Auth for Django tutorial](https://github.com/davisfreeman1015/SocialAuthDjangoTutorial)
  will show you how to integrate social media sign in buttons into your Django
  application.

* [Django Wall of Shame (WOS)](http://djangowos.com/) shows packages that
  are Python 3 compatible in green and ones that are not yet compatible with
  Python 3 in red.

* Luke Plant writes about 
  [his approach to class based views](http://lukeplant.me.uk/blog/posts/my-approach-to-class-based-views/) (CBVs),
  which often provoke heated debate in the Django community for whether they
  are a time saver or "too much magic" for the framework.

* [How to serve Django apps with uWSGI and Nginx on 14.04](https://www.digitalocean.com/community/tutorials/how-to-serve-django-applications-with-uwsgi-and-nginx-on-ubuntu-14-04)
  is a detailed tutorial that walks through each step in the deployment process.


## Django videos
<div class="well" style="margin-top: 20px;">
Looking for Django videos instead of just articles? There's a special section
for Django and web development on the 
<a href="/best-python-videos.html">Best Python Videos</a> page.
</div>


## Django migrations
* Paul Hallett wrote a 
  [detailed Django 1.7 app upgrade guide](https://www.twilio.com/blog/2014/10/upgrading-your-django-reusable-app-to-support-django-1-7.html) 
  on the Twilio blog from his experience working with the django-twilio 
  package.

* Real Python's [migrations primer](https://realpython.com/blog/python/django-migrations-a-primer/)
  explores the difference between South's migrations and the built-in
  Django 1.7 migrations as well as how you use them.

* Andrew Pinkham's "Upgrading to Django 1.7" series is great learning
  material for understanding what's changed in this major release and
  how to adapt your Django project.
  [Part 1](http://andrewsforge.com/article/upgrading-django-to-17/part-1-introduction-and-django-releases/),
  [part 2](http://andrewsforge.com/article/upgrading-django-to-17/part-2-migrations-in-django-16-and-17/) and
  [part 3](http://andrewsforge.com/article/upgrading-django-to-17/part-3-django-17-new-features/)
  and
  [part 4](http://andrewsforge.com/article/upgrading-django-to-17/part-4-upgrade-strategies/)
  are now all available to read.


## Django testing
* [Integrating Front End Tools with Django](https://lincolnloop.com/blog/integrating-front-end-tools-your-django-project/)
  is a good post to read for figuring out how to use [Gulp](http://gulpjs.com/)
  for handling front end tools in development and production Django sites.

* [Getting Started with Django Testing](http://howchoo.com/g/mjkwmtu5zdl/getting-started-with-django-testing)
  will help you stop procrastinating on testing your Django projects if you're
  uncertain where to begin.

* [Testing in Django](https://realpython.com/blog/python/testing-in-django-part-1-best-practices-and-examples/)
  provides numerous examples and explanations for how to test your Django
  project's code.

* [Django views automated testing with Selenium](https://medium.com/@unary/django-views-automated-testing-with-selenium-d9df95bdc926)
  gives some example code to get up and running with 
  [Selenium](http://www.seleniumhq.org) browser-based tests.


## Django with Angular (Djangular) resources
* [Getting Started with Django Rest Framework and AngularJS](http://blog.kevinastone.com/getting-started-with-django-rest-framework-and-angularjs.html)
  is a very detailed introduction to Djangular with example code. 

* [Building Web Applications with Django and AngularJS](https://thinkster.io/brewer/angular-django-tutorial/)
  is a very detailed guide for using Django as an API layer and AngularJS
  as the MVC front end in the browser.

* This [end to end web app with Django-Rest-Framework & AngularJS part 1](http://blog.mourafiq.com/post/55034504632/end-to-end-web-app-with-django-rest-framework)
  tutorial along with 
  [part 2](http://blog.mourafiq.com/post/55099429431/end-to-end-web-app-with-django-rest-framework),
  [part 3](http://blog.mourafiq.com/post/58725341511/end-to-end-web-app-with-django-rest-framework)
  and
  [part 4](http://blog.mourafiq.com/post/58726121556/end-to-end-web-app-with-django-rest-framework)
  creates an example blog application with Djangular. There is also a
  corresponding [GitHub repo](https://github.com/mouradmourafiq/django-angular-blog)
  for the project code.


## Django ORM resources
The [Django ORM](https://docs.djangoproject.com/en/dev/topics/db/) works well
for simple and medium-complexity database operations. However, there are often
complaints that the ORM makes complex queries much more complicated than
writing straight SQL or using [SQLAlchemy](http://www.sqlalchemy.org/). 

It's technically possible to drop down to SQL but it ties the queries to a 
specific database implementation. The ORM is coupled closely with Django so
replacing the default ORM with SQLAlchemy is currently a hack workaround. Note
though that some of the Django core committers believe it is only a matter of
time before the default ORM is replaced with SQLAlchemy. It will be a large
effort to get that working though so it's likely to come in Django 1.9 or 
later.

Since the majority of Django projects are tied to the default ORM, it's best to
read up on advanced use cases and tools for doing your best work within the
existing framework.

* [Django models, encapsulation and data integrity](http://www.dabapps.com/blog/django-models-and-encapsulation/)
  is a detailed article by Tom Christie on encapsulating Django models for
  data integrity.

* [Django Debug Toolbar](http://django-debug-toolbar.readthedocs.org/en/1.2/) 
  is a powerful Django ORM database query inspection tool. Highly recommended
  during development to ensure you're writing reasonable query code. 
  [Django Silk](http://mtford.co.uk/blog/2/) is another inspection tool and
  has capabilities to do more than just SQL inspection.

* [Making a specific Django app faster](http://reinout.vanrees.org/weblog/2014/05/06/making-faster.html)
  is a Django performance blog post with some tips on measuring performance
  and optimizing based on the measured results.

* [Why I Hate the Django ORM](https://speakerdeck.com/alex/why-i-hate-the-django-orm)
  is Alex Gaynor's overview of the bad designs decisions, some of which he
  made, while building the Django ORM.

* [Going Beyond Django ORM with Postgres](https://speakerdeck.com/craigkerstiens/going-beyond-django-orm-with-postgres)
  is specific to using PostgreSQL with Django.

* [Migrating a Django app from MySQL to PostgreSQL](http://www.calazan.com/migrating-django-app-from-mysql-to-postgresql/)
  is a quick look at how to move from MySQL to PostgreSQL. However, my guess
  is that any Django app that's been running for awhile on one relational
  database will require a lot more work to port over to another backend
  even with the power of the ORM.

* [Django Model Descriptors](http://blog.kevinastone.com/django-model-descriptors.html)
  discusses and shows how to incorporate business logic into Django models
  to reduce complexity from the views and make the code easier to reuse across
  separate views.

* [Supporting both Django 1.7 and South](http://treyhunner.com/2014/03/migrating-to-django-1-dot-7/)
  explains the difficulty of supporting Django 1.7 and maintaining South 
  migrations for Django 1.6 then goes into how it can be done.

* [Adding basic search to your Django site](https://www.calazan.com/adding-basic-search-to-your-django-site/)
  shows how to write generic queries that'll allow you to provide site 
  search via the Django ORM without relying on another tool like 
  ElasticSearch. This is great for small sites before you scale them up with
  a more robust search engine.

* [How to use Django's Proxy Models](https://www.wellfireinteractive.com/blog/using-django-proxy-models)
  is a solid post on a Django ORM concept that doesn't frequently get a lot
  of love or explanation.

* [Tightening Django Admin Logins](http://tech.marksblogg.com/django-admin-logins.html)
  shows you how to log authentication failures, create an IP addresses white
  list and combine fail2ban with the authentication failures list.

* [Django 1.7: Database Migrations Done Right](https://markusholtermann.eu/2014/09/django-17-database-migrations-done-right/)
  explains why South was not directly integrated into Django, how migrations
  are built and shows how backwards migrations work.


## Static and media files
Deploying and handling static and media files can be confusing for new
Django developers. These resources along with the 
[static content](/static-content.html) page are useful for figuring out how 
to handle these files properly.

* [Using Amazon S3 to Store your Django Site's Static and Media Files](http://www.caktusgroup.com/blog/2014/11/10/Using-Amazon-S3-to-store-your-Django-sites-static-and-media-files/)
  is a well written guide to a question commonly asked about static and
  media file serving.

* [Loading Django FileField and ImageFields from the file system](http://www.revsys.com/blog/2014/dec/03/loading-django-files-from-code/)
  shows how to load a model field with a file from the file system.

* [Restricting access to user-uploaded files in Django](http://blog.wearefarm.com/2015/02/09/contact-form-uploads/)
  provides a protection mechanism for media files.



## Open source Django example projects
* [Txt 2 React](https://github.com/makaimc/txt2react) is a full Django web
  app that allows audiences to text in during a presentation with feedback
  or questions.

* [Openduty](https://github.com/ustream/openduty) is a website status checking
  and alert system similar to PagerDuty.

* [Courtside](https://github.com/myusuf3/courtside) is a pick up sports web 
  application written and maintained by the author of PyCoder's Weekly.

* These two Django Interactive Voice Response (IVR) system web application
  repositorities [part 1](https://github.com/phalt/twilio-django-part-1) and
  [part 2](https://github.com/phalt/twilio-django-part-2) show you how to
  build a really cool Django application. There's also an accompanying 
  [blog post](https://www.twilio.com/blog/2014/07/build-an-ivr-system-with-twilio-and-django.html)
  with detailed explanations of each step.

* [Taiga](https://github.com/taigaio/taiga-back) is a project management
  tool built with Django as the backend and AngularJS as the front end.


## Django project templates
* [Caktus Group's Django project template](https://github.com/caktus/django-project-template) 
  is Django 1.6+ ready.

* [Cookiecutter Django](https://github.com/pydanny/cookiecutter-django) is a 
  project template from Daniel Greenfeld, for use with Audrey Roy's 
  [Cookiecutter](https://github.com/audreyr/cookiecutter). Heroku 
  deployment-ready.

* [Two Scoops Django project template](https://github.com/twoscoops/django-twoscoops-project)
  is also from the PyDanny and Audrey Roy. This one provides a quick scaffold
  described in the Two Scoops of Django book.


## Django learning checklist
1. [Install Django](https://docs.djangoproject.com/en/dev/topics/install/) on
   your local development machine.

1. Work through the initial 
   ["polls" tutorial](https://docs.djangoproject.com/en/dev/intro/tutorial01/).
 
1. Build a few more simple applications using the tutorial resources found
   in the "Django resources" section.

1. Start coding your own Django project with help from the 
   [official documentation](https://docs.djangoproject.com/en/dev/) and 
   resource links below. You'll make plenty of mistakes which is critical
   on your path to learning the right way to build applications.

1. Read [2 Scoops of Django](http://www.amazon.com/Two-Scoops-Django-Best-Practices/dp/098146730X/ref=sr_1_2?ie=UTF8&qid=1391562062&sr=8-2&tag=mlinar-20) 
   to understand Django best practices and learn better ways of building 
   Django web applications.

1. Move on to the [deployment section](/deployment.html) to get your Django 
   project on the web.


### What do you need to learn next for your Django app?
