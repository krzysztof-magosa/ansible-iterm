Iterm Ansible Role
==================

This role installs iTerm on OS X.  
By default installs version 2.1.1 (latest-stable) from official website.

Role Variables
--------------

* iterm_version - specifies version to be installed, must reflect value from `/Applications/iTerm.app/Contents/Info.plist`
* iterm_url - url to download setup zip from

Example Playbook
----------------

    - hosts: localhost
      roles:
         - { role: krzysztof-magosa.iterm }

License
-------

MIT
