CKANEXT-NHSEngland
------------------

A plugin that modifies a basic CKAN instance to fulfil the following:

* Some simple CSS updates to make a CKAN site look like it belongs to NHSEngland.
* Static pages required by NHSEngland.
* Custom fields for metadata associated with datasets required by NHSEngland.

Installation Instructions
-------------------------

* Activate the CKAN virtualenv
* Clone the repository to /usr/lib/ckan/default/src
* cd into ckanext-nhsengland
* $ python setup.py develop

Configure CKAN:

* Add to ckan.plugins: nhsengland_skin
* Change ckan.site_logo to: /images/nhsengland_logo.png
