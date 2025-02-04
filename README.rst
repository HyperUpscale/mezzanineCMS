.. image:: https://img.shields.io/pypi/v/mezzanine.svg
   :target: https://pypi.org/project/mezzanine/
.. image:: https://img.shields.io/pypi/pyversions/mezzanine.svg
   :target: https://pypi.org/project/mezzanine/
.. image:: https://img.shields.io/pypi/djversions/mezzanine.svg
   :target: https://pypi.org/project/mezzanine/
.. image:: https://github.com/stephenmcd/mezzanine/workflows/Test%20and%20release/badge.svg
   :target: https://github.com/stephenmcd/mezzanine/actions?query=workflow%3A%22Test+and+release%22
.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black

Created by `Stephen McDonald <http://twitter.com/stephen_mcd>`_

========
Overview
========

Mezzanine is a robust and flexible content management platform built on the Django framework.
Its simple yet highly extensible architecture encourages hands-on code exploration. Mezzanine is BSD licensed and backed by an active community.

Similar to tools like WordPress, Mezzanine offers an intuitive interface for managing various content types. However, unlike other platforms relying on numerous modules, Mezzanine delivers most functionality out of the box, resulting in a more integrated and efficient platform.

==============
 How I run it 
==============
On WSL with Ubuntu 20.04 and python3 (Python 3.8.10) 

You can install it without 

1: git clone https://github.com/HyperUpscale/mezzanineCMS.git && cd mezzanineCMS && pip install . && mezzanine-project newproject && cd newproject
  
2: python3 manage.py createdb
   ---> it will ask you politely to create account and if you want install some initial demo pages

3: python3 manage.py runserver

You should see this:

.. image::  https://github.com/HyperUpscale/mezzanineCMS/blob/36172b339872d40c4084258ac1974fabff6b63b5/docs/img/mez-installed.PNG


Alternatively (I guess) it should also work N Windows 10 with Python 3.10:
--------------------------------------------------------------------------
0. On windows and you want with virtual Environment.
   - python -m venv VirtualPythonEnv && VirtualPythonEnv\Scripts\activate 
1. pip install mezzanine
2. mezzanine-project myproject
3. cd myproject && python manage.py createdb
4. python manage.py runserver


Features
========

In addition to the usual features provided by Django such as MVC
architecture, ORM, templating, caching and an automatic admin
interface, Mezzanine provides the following:

* Hierarchical page navigation
* Save as draft and preview on site
* Scheduled publishing
* Drag-and-drop page ordering
* WYSIWYG editing
* `In-line page editing`_
* Drag-and-drop HTML5 forms builder with CSV export
* SEO friendly URLs and meta data
* Ecommerce / Shopping cart module (`Cartridge`_)
* Configurable `dashboard`_ widgets
* Blog engine
* Tagging
* `Free Themes`_ Marketplace
* User accounts and profiles with email verification
* Translated to over 35 languages
* Sharing via Facebook or Twitter
* `Multi-lingual sites`_
* `Custom templates`_ per page or blog post
* `Twitter Bootstrap`_ integration
* API for `custom content types`_
* `Search engine and API`_
* Seamless integration with third-party Django apps
* One step migration from other blogging engines
* `Disqus`_ integration, or built-in threaded comments
* `Gravatar`_ integration
* `Google Analytics`_ integration
* `bit.ly`_ integration
* `Akismet`_ spam filtering
* `JVM`_ compatible (via `Jython`_)




.. image:: https://github.com/HyperUpscale/mezzanineCMS/blob/29a18662543c01c3e8457893146ed037398c3a9b/docs/img/mez1.PNG


The Mezzanine admin dashboard:

.. image:: https://github.com/HyperUpscale/mezzanineCMS/blob/0e25ef8db8bc1e0a2911e488ce87eb7dcde972e1/docs/img/mez-admin.PNG
.. image:: https://github.com/HyperUpscale/mezzanineCMS/blob/29a18662543c01c3e8457893146ed037398c3a9b/docs/img/graph.png

Donating
========

If you would like to make a donation to continue development of
Mezzanine, you can do so via the `Mezzanine Project`_ website.


Quotes
======

* "I'm enjoying working with Mezzanine, it's good work"
  - `Van Lindberg`_, `Python Software Foundation`_ chairman
* "Mezzanine looks like it may be Django's killer app"
  - `Antonio Rodriguez`_, ex CTO of `Hewlett Packard`_, founder
  of `Tabblo`_
* "Mezzanine looks pretty interesting, tempting to get me off
  Wordpress" - `Jesse Noller`_, Python core contributor,
  `Python Software Foundation`_ board member
* "I think I'm your newest fan. Love these frameworks"
  - `Emile Petrone`_, integrations engineer at `Urban Airship`_
* "Mezzanine is amazing" - `Audrey Roy`_, founder of `PyLadies`_
  and `Django Packages`_
* "Mezzanine convinced me to switch from the Ruby world over
  to Python" - `Michael Delaney`_, developer
* "Like Linux and Python, Mezzanine just feels right" - `Phil Hughes`_,
  Linux For Dummies author, `The Linux Journal`_ columnist
* "Impressed with Mezzanine so far" - `Brad Montgomery`_, founder
  of `Work For Pie`_
* "From the moment I installed Mezzanine, I have been delighted, both
  with the initial experience and the community involved in its
  development" - `John Campbell`_, founder of `Head3 Interactive`_
* "You need to check out the open source project Mezzanine. In one
  word: Elegant" - `Nick Hagianis`_, developer


.. _`Django`: http://djangoproject.com/
.. _`Django Code of Conduct`: https://www.djangoproject.com/conduct/
.. _`Wordpress`: http://wordpress.org/
.. _`BSD licensed`: http://www.linfo.org/bsdlicense.html
.. _`great sites people have built using Mezzanine`: http://mezzanine.jupo.org/sites/
.. _`Mezzanine project page`: http://mezzanine.jupo.org
.. _`In-line page editing`: http://mezzanine.jupo.org/docs/inline-editing.html
.. _`custom content types`: http://mezzanine.jupo.org/docs/content-architecture.html#creating-custom-content-types
.. _`Cartridge`: http://cartridge.jupo.org/
.. _`Search engine and API`: http://mezzanine.jupo.org/docs/search-engine.html
.. _`dashboard`: http://mezzanine.jupo.org/docs/admin-customization.html#dashboard
.. _`Free Themes`: https://github.com/thecodinghouse/mezzanine-themes
.. _`Custom templates`: http://mezzanine.jupo.org/docs/content-architecture.html#page-templates
.. _`Multi-lingual sites`: http://mezzanine.jupo.org/docs/multi-lingual-sites.html
.. _`JVM`: http://en.wikipedia.org/wiki/Java_virtual_machine
.. _`Jython`: http://www.jython.org/
.. _`Twitter Bootstrap`: http://getbootstrap.com/
.. _`Disqus`: http://disqus.com/
.. _`Gravatar`: http://gravatar.com/
.. _`Google Analytics`: http://www.google.com/analytics/
.. _`bit.ly`: http://bit.ly/
.. _`Akismet`: http://akismet.com/
.. _`GitHub`: http://github.com/stephenmcd/mezzanine/
.. _`Bitbucket`: http://bitbucket.org/stephenmcd/mezzanine/
.. _`mezzanine-users`: http://groups.google.com/group/mezzanine-users/topics
.. _`core-team@mezzaninecms.com`: mailto:core-team@mezzaninecms.com?subject=Mezzanine+Security+Issue
.. _`GitHub issue tracker`: http://github.com/stephenmcd/mezzanine/issues
.. _`#mezzanine IRC channel`: irc://irc.freenode.net/mezzanine
.. _`Freenode`: http://freenode.net
.. _`Mezzanine Project`: http://mezzanine.jupo.org

.. _`Python Software Foundation`: http://www.python.org/psf/
.. _`Urban Airship`: http://urbanairship.com/
.. _`Django Packages`: http://djangopackages.com/
.. _`Hewlett Packard`: http://www.hp.com/
.. _`Tabblo`: http://www.tabblo.com/
.. _`The Linux Journal`: http://www.linuxjournal.com
.. _`Work For Pie`: http://workforpie.com/
.. _`Van Lindberg`: http://www.lindbergd.info/
.. _`Antonio Rodriguez`: http://an.ton.io/
.. _`Jesse Noller`: http://jessenoller.com/
.. _`Emile Petrone`: https://twitter.com/emilepetrone
.. _`Audrey Roy`: http://cartwheelweb.com/
.. _`Michael Delaney`: http://github.com/fusepilot/
.. _`John Campbell`: http://head3.com/
.. _`Phil Hughes`: http://www.linuxjournal.com/blogs/phil-hughes
.. _`Nick Hagianis`: http://hagianis.com
.. _`Brad Montgomery`: http://blog.bradmontgomery.net
.. _`Head3 Interactive`: http://head3.com
.. _`PyLadies`: http://www.pyladies.com
