nginxproxy
========

Configures a proxy on a nginx server.

Requirements
------------

None.

Role Variables
--------------

*server*
The fqdn of the server to be proxied.

*proxy*
The URL of the proxy server.

*name*
The name of the config file to write.

Dependencies
------------

none

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: proxy
      roles:
         - { role: craigmj.nginxproxy, server:"craigmj.com www.craigmj.com", proxy: "localhost:12345", name: "craigmj.com" }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
