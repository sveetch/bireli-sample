.. _Python: https://www.python.org/
.. _Django: https://www.djangoproject.com/
.. _Node.js: https://nodejs.org/dist/latest-v16.x/docs/api/
.. _NPM: https://docs.npmjs.com/
.. _Bootstrap: https://getbootstrap.com/docs/
.. _project-composer: https://github.com/sveetch/project-composer
.. _Webpack: https://webpack.js.org/
.. _django-configurations: https://django-configurations.readthedocs.io/
.. _Bireli: https://cookiecutter-bireli.readthedocs.io/en/0.5.1/

=============
release-0-5-1
=============

A sample project built from Bireli 0.5.1


Main stack components
*********************

* `Python`_ >=3.11;
* `Django`_ >=5.2,<6.0;
* `project-composer`_ >=0.7.0,<0.8.0;
* `django-configurations`_ >=2.5.1,<2.6.0;
* `Node.js`_ >=18.14.0;
* `NPM`_ >=10.0.0;
* `Bootstrap`_ 5.3.6;

First steps
***********

This project has been generated from ``cookiecutter-bireli==0.5.1``.
You may learn more about your project usage on `Bireli`_ documentation.


Quick install
*************

Install backend and frontend, then build frontend and finally add some dummy initial
datas: ::

    make install frontend

You will need an admin user, create it with: ::

    make superuser

Once finished, you may ensure everything is working as expected with: ::

    make quality


Quick usage
***********

Just run the development server: ::

    make run

And open your browser on ``http://localhost:8001/``.


Further
*******

There is a lot of useful Makefile tasks to manage your project, read the Makefile
help: ::

    make help

And see `Bireli`_ documentation about project usage to know more.
