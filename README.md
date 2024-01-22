#  A Django Resume Project from Development to Deployment and collectstatic in Django
  A Django Resume Project from Development to Deployment and collectstatic in Django



Deployment on PythonAnywhere.
steps -
1 ) -Pull your code down to PythonAnywhere using a Bash console and setup a virtualenv

2 ) -Set your config variables in the postactivate script

3) - Run the manage.py migrate and collectstatic commands. If you’ve opted for django-compressor, also run compress

4 ) - Add an entry to the PythonAnywhere Web tab

5 ) -Set your config variables in the PythonAnywhere WSGI config file

Once you’ve been through this one-off config, future deployments are much simpler: just git pull and then hit the “Reload” button :)Deployment on PythonAnywhere. steps - 1 ) -Pull your code down to PythonAnywhere using a Bash console and setup a virtualenv 2 ) -Set your config variables in the postactivate script 3) - Run the manage.py migrate and collectstatic commands. If you’ve opted for django-compressor, also run compress 4 ) - Add an entry to the PythonAnywhere Web tab 5 ) -Set your config variables in the PythonAnywhere WSGI config file Once you’ve been through this one-off config, future deployments are much simpler: just git pull and then hit the “Reload” button :)
Skills: Cascading Style Sheets (CSS) · HTML · Django
