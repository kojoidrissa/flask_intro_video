My notes from the video series on Flask
========================================

Follow-up points
-----------------
-  Jinja2 Macros

    +  In example 2e, he starts using macros (functions in Jinja2 templates). I need to play with these more to better internalize them

-  Twitter bootstrap

    +  `Bootstrap docs <http://getbootstrap.com/getting-started/#examples>`_
    +  Although not critical for Flask, I'm also using it with my blog and the Django Girls tutorial uses it. So, I need to be more familiar with it.
    +  The examples in 2F start using it much more. Specifically, via the ``flask-bootstrap`` module. See the inclusion of bootstrap classes in ``macros.html``.
    +  In 2g, ``page_content`` is HIS block name from HIS ``base.html``. Thus, other pages that inherit from it will need to place THEIR content in a ``page_content`` div.

-  Decorators: I need to read more about those. Probalby in *Introducing Python* or somewhere else. They come up in Flask AND in testing and OO code (class methods, etc)