* Description
  This repository contains general-purpose, useful patches for Drupal. 

* Usage
  These patches are meant to be incuded in a Drush .make file:

projects[drupal][patch][] = http://github.com/jrbeeman/drupal-patches/raw/master/htaccess-force_to_ssl.patch

* Patches

** htaccess-force_to_ssl.patch
   Force all requests to SSL using generic rewrites.
