Step 1 - Install ansible and python on the master machine

Steps to be followed for running Playbook on local server

1. Give host as "hosts: 127.0.0.1"
2. Another argument will be "connection: local"
3. If getting python intrepreter error then we have to search for the python version use "which python" or "which python3" and we will get the location
4. Now we have to specify the python version as a variable, to do that put this inside vars "ansible_python_interpreter: /usr/bin/python3"
5. Now we have succesfully setup the ansible locally and now we can run our playbooks to get the desired output
