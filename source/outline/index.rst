Django Paper Outline
====================

**Thesis:** A Django web application is time consuming to set up, but once it is
set up, the Django framework and out-of-the-box features make the long set up
worth it.

* What is Django?

    * Describe what Django is
    * Talk about who uses Django (Use source [#f2])
    * Talk popularity among other python web frameworks
      (Use source [#f1] open source section)
    * Quickly state other python frameworks

* Django takes time to set up

    * Main Disadvantage of Django is long setup
    * Overview on setting up "Hello World" (Use source [#f4] )
      (Include code samples and screen shots on set up)
    * Overview of other python based app set ups

        * Talk about Flask setup and how much easier/faster it is to set up
          (Use source [#f1])

    * Not suited for small scale projects (Use source [#f2])

* Intro to Various Django features which makes Django popular and gives
  Django the advantage over other python frameworks

    * Framework
    * ORM
    * Out of the box extra features

* Framework

    * MVT architecture (Show figure from source [#f2])
    * Talk about models

        * Is a python class
        * Keeps your business logic
        * Generally each model maps to one database table

    * Talk about views

        * Accepts HTTP requests
        * Applies the models/python classes
        * Provides HTTP responses or provides data to templates

    * Talk about templates

        * Is simply HTML code to show data
        * Can be static or dynamic

    * Can adjust visual part of app and logic separately
    * Asynchronous Views

* ORM in Django (Use source [#f5])

    * ORM is a Object Relational Mapper
    * Allows queries on databases without raw SQL
    * Include and talk about cool figure in source 2 explaining ORM
    * Speeds up web application development
    * Include an example from source 5 (Show code snippets)

* Out of the box web security features (Use source [#f3])

    * Security against most common web-attacks
    * cross-site scripting

        * Django templates escape dangerous characters

    * cross-site request forgeries

        * Works by checking for a secret (through a cookie) in each POST request

    * SQL-injection


* Out of the box Account management & Authentication ([#f1] and [#f3])

    * Log-ins and log-outs
    * Web apps requires authentication to know who you are
    * Web apps requires authorization to know what you are allowed to do/see

* Out of the box admin panel ([#f1] and [#f2])

    * Is a user interface for managing data for CRUD applications
    * No extra code is needed to do CRUD activities
    * Not included in other python frameworks


.. [#f1] Herman, M. (2020, October 28). "`Django vs. Flask in 2020: Which Framework to Choose. <https://testdriven.io/blog/django-vs-flask/>`_" Test Driven Labs.
.. [#f2] Zublenko, E. "`Why Django is the Best Web Framework for Your Project. <https://steelkiwi.com/blog/why-django-best-web-framework-your-project/>`_" SteelKiwi INC.
.. [#f3] Grehan, R. (2011, August 10). "`Pillars of Python: Django Web framework; Django combines excellent backward compatibility, good admin tools, and a focus on developer ease <https://link.gale.com/apps/doc/A263931054/GPS?u=simpsoncoll&sid=GPS&xid=22b37d98>`_" InfoWorld.com.
.. [#f4] Dauzon, S., Bendoraitis, A., & Ravindran, A. (2016). "`Django: Web Development with Python. <https://search.ebscohost.com/login.aspx?direct=true&AuthType=ip,url,uid,cookie&db=e000xna&AN=1345264&site=ehost-live&scope=site>`_" Packt Publishing.
.. [#f5] Ljødal, S. (2019) "`Pushing the ORM to its limits. <https://2019.djangocon.eu/talks/pushing-the-orm-to-its-limits/>`_" DjangoCon 2019, Copenhagen, Denmark.
.. [#f6] "`Security in Django. <https://docs.djangoproject.com/en/2.2/topics/security/>`_" Django Software Foundation.