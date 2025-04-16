Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).


GitHub not authenticating with Ansible-Master with username and password, follow these steps:
1.ssh-keygen -t ed25519 -C "your_email@example.com"
2.cat ~/.ssh/id_ed25519.pub
🌐 3. Add your SSH key to GitHub:
Go to: https://github.com/settings/keys

Click New SSH Key

Title: ansible-master (or anything meaningful)

Paste your public key

Click Add SSH key
4.git remote set-url origin git@github.com:DeeptiSingh2409/ansible-role.git
5.git push -u origin master

