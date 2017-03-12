Docker Elasticsearch
=========

Installs elasticsearch 5.2.x as a docker container exposed on port 9200 and 9300.


Role Variables
--------------

There are no variables

Dependencies
------------

Requires dustinrue.docker and dustinrue.xenial-bootstrap

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - dustinrue.xenial-bootstrap
         - dustinrue.docker
         - dustinrue.docker-elasticsearch

License
-------

MIT