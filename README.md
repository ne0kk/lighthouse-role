lighthouse-role

=========

роль для установки lighthouse

Requirements
------------

centos7
nginx
unzip

Role Variables
--------------

nginx.conf.yml
/etc/nginx/nginx.conf

Dependencies
------------

NOt

Example Playbook
----------------

lighthouse:
  hosts:
    lighthouse-01:
      ansible_host: 89.169.147.239
      ansible_private_key_file: ~/.ssh/id_rsa
      ansible_ssh_user: centos


License
-------

BSD

Author Information
------------------

github.com/ne0kk/lighthouse-role
