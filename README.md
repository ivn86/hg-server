Ansible Mercurial server
========================

Ansible playbook for installs and configure Mercurial server on Debian. More information [at my blog](https://www.zharenkov.ru/post/ansible-mercurial-server-install)

Example Playbook
----------------

    - hosts: hgsrv
      remote_user: root
      roles:
      - hg-server

License
-------

BSD

Author Information
------------------

Ivan Zharenkov <ivan@zharenkov.ru>
