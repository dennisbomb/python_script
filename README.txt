# Starting from version 3.5, it is recommended that Python use venv to create virtual environments:Setting Up the Environment

https://pynet.twb-tech.com/blog/netmiko-and-textfsm.html

$ python3.8 -m venv .venv


To move to a virtual environment, you should execute command:

$ source .venv/bin/activate


To exit virtual environment, use command “deactivate”:

$ deactivate


List of modules to be installed in vEnv:

$ pip install pytest pytest-clarity pyyaml tabulate jinja2 textfsm pexpect netmiko graphviz