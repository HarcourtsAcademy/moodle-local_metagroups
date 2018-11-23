Moodle Meta-course Group Synchronization
=========================================

Requirements
------------
- Moodle 3.3 (build 2017051500) or later.
- Meta-course enrolment (build 2017050500) or later.

Installation
------------
Copy the metagroups folder into your Moodle /local directory and visit your Admin Notification page to complete the installation.

Usage
-----
After installation, or when creating new meta-course enrolment instances, you may need to synchronize existing groups. To do this
run the cli/sync.php script (use the --help switch for further instructions on usage).

Any future amendments to groups (add, update and delete) and their membership (add or remove users) in 'child' courses will be automatically
reflected in 'parent' courses that use groups.

Author
------
Paul Holden (pholden@greenhead.ac.uk)

- Updates: https://moodle.org/plugins/view.php?plugin=local_metagroups
- Latest code: https://github.com/paulholden/moodle-local_metagroups
