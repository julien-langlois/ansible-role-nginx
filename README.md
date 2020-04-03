Ansible Role: Nginx
=========

This role allows the installation of a Nginx web server and the configuration of:

- Nginx configuration
- vhosts (server block)
- whether or not to remove the default vhost
- Gzip
- Brotli (on request)
- Auth Restriction (.htpasswd)
- SSL
- PHPMyAdmin (if installed)

Requirements
------------

None.

Role Variables
--------------

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: julien_langlois.nginx }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2020 by [Julien Langlois](https://github.com/julien-langlois).
