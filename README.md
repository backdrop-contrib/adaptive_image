Adaptive Image
==============

The Adaptive image module provides device-appropriate versions of images from your fields.
You can activate adaptive images by adding an adaptive effect to any of your image styles.

The used technique is derived from http://adaptive-images.com/ by Matt Wilcox.
The hard work is done by Drupal core no need for any additional rewrites.
If image styles work on your website, this module will too.

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Tested
 - Known Issues
 - Special Thanks
 - Requirements
 - Installation
 - Coming From Drupal?
 - Usage
 - License
 - Credits
 - Maintainers

TESTED
-----

Working in Backdrop 1.4.

KNOWN ISSUES
---------------------

None -- this is a simple module that requires manual effort in the image styles to see any effect.

SPECIAL THANKS
--------------

erdfisch - Sponsored development

REQUIREMENTS
------------

Javascript enabled on your website.

INSTALLATION
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules


COMING FROM DRUPAL?
-------------------

Nothing substantial changed from the port of 7.x-1.4

PERMISSIONS
------------

none

USAGE
-----

1.

- Go to admin/config/media/image-styles

- Edit an existing or add a new style. Add the Adaptive image effect.

- Click on 'Update style' button.

2.

- Go to admin/structure/types

- Click on "manage display".

- Choose a "image" field and click on the edit button.

- Choose the previously updated style as image style.

- Click on "Update".


LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

CREDITS
-----------

<https://www.drupal.org/u/sanduhrs>

MAINTAINERS
-----------

- seeking or biolithic <https://github.com/biolithic>

Ported to Backdrop by:

- biolithic <https://github.com/biolithic>
