Taxonomy Term Status
====================

This module adds a status-flag to taxonomy terms. Using this flag it is
possible to specify whether terms should be published or not. Users with the
appropriate permission may access unpublished terms.

The module also integrates with views by exporting the term status as a views
field. It also exposes actions which may be used for integration with rules
and views bulk operations.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.
- Review and set permissions in Admin -> People -> Permissions
- Rebuild term status records for existing terms in
    Admin -> Config -> System -> Taxonomy Term Status
- Edit your vocabularies and specify the default status for newly created
    terms. (optional).

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/termstatus/issues).

Current Maintainers
-------------------

- [Giant Rabbit](https://github.com/giant-rabbit).

Credits
-------

- Ported to Backdrop CMS by [Giant Rabbit](https://github.com/giant-rabbit).
- Originally written for Drupal by [znerol](https://git.drupalcode.org/znerol).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
