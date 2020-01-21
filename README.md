Role Name
=========

Role is userManagement.
Therefore create a folder name called roles and go to that folder.
Then, clone this repository.
Next come out of the roles directory. Then, copy the host file and usersetup.yml file from templates.

Requirements
------------

Update usersetup.yml file variables directory accordingly.

Role Variables
--------------

vars/main.yml has the variable and it contains the user password.


Dependencies
------------

Role is userManagement.
Therefore create a folder name called roles and go to that folder.
Then, clone this repository.
Next come out of the roles directory. Then, copy the host file and usersetup.yml file from templates.


Example Playbook
----------------
Then execute following command from outside the roles directory.
ansible-playbook usersetup.yml

Also, the following command will list the tags and run the tags accordingly.
ansible-playbook usersetup.yml --list-tags

For example to run the listed tags, execute the following command:
ansible-playbook usersetup.yml -t add_new_user

-t flag let you use the tags. The above playbook will only add the new user using the tags.

License
-------

BSD

Author Information
------------------

Sushan Kunwar
Sytem Engineer/Devops Engineer
