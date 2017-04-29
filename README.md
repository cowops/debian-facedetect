Debian-Facedetect
=================

A simple face detector for batch processing

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-facedetect }

Tasks
-----

  - Install dependencies
  - Install [FaceDetect](http://www.thregr.org/~wavexx/hacks/facedetect/)

License
-------

BSD
