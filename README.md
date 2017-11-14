Role Name
=========

Write version.txt file with latest git tag of playbook

Requirements
------------

None

Role Variables
--------------

- version_git_tag_file: full path of version file to write. (es: /tmp/version.txt)
- version_git_repo_path: git repository path from wich extract tag. Default '../' for playbook repository

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - version-git-tag

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
