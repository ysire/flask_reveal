flask_reveal
============

The Easiest Way to Present Online

This is a backend implement like [slid.es](http://slid.es), Use [flask](https://github.com/mitsuhiko/flask)/[mongoengine](https://github.com/MongoEngine/mongoengine)

First say thank to [hakimel](https://github.com/hakimel) and his [reveal.js](https://github.com/hakimel/reveal.js)

I Use [python-social-auth)](https://github.com/omab/python-social-auth) for social auth, but it do not support mongoengine ,and I rewrote some code to achieve my thoughts

About
=====

* default, with This you can use Your Bitbucket/Google/Github/Instagram/Linkdln/Trello/Tumblr/Stackoverflow Account by oauth/oauth2 login
* You can create/edit/delete/save your HTML or markdown presentation

Usage
=====

You must edit the settings.py with your settings, a example settings has exist:

    cp settings.py.example settings.py
