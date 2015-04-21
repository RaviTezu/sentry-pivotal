sentry-pivotal
==============

An extension for Sentry which integrates with Pivotal Tracker. Specifically, it allows you to easily create
stories from events within Sentry.


Install
-------

Install the package via ``pip``::

    pip install sentry-pivotal

Configuration
--------------
- Go to your project page (https://<sentry-url>/<organization>/<project>/settings/) and click on "Manage Integrations". 
- Enable the "Pivotal Tracker" plugin by clicking on the checkbox next to it and then click on "Save Changes" button.
- Now you should see the "Pivotal Tracker" option under the "INTEGRATIONS" tab or Please refresh your page.
- Click on the "Pivotal Tracker" option and Enter the "API Token" and "Project ID" values and click on Save Changes" button.
- Now, you should be able to see "Add Story" button the right side on the event page. 
