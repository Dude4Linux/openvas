TKLtemplate - Template for starting a NEW TurnKey GNU/Linux appliance
=====================================================================

`TKLtemplate` is an open source application licensed under the GPL.

Description or Purpose
----------------------
.. Briefly describe what the template does 

This template is meant to be used when starting a new TurnKey GNU/Linux appliance.
Do not use when forking an existing appliance, instead follow the `Guidelines`_.

Usage
-----
.. Describe the steps for using the template below

Create a new project repository on GitHub
'''''''''''''''''''''''''''''''''''''''''
* Log into `GitHub`_, and browse to your home directory.
* Click on the ``Repositories`` tab; then click the ``New`` button.
* Enter a repository name appropriate for the new appliance.

Note: GitHub will offer to create a README.rst file. Leave the option unchecked.

Clone the repository
''''''''''''''''''''
To be able to work on the project you'll need to clone it::

On your TKLdev workstation, enter

    cd projects    
    git clone git@github.com:USERNAME/PROJECTNAME.git    
    cd PROJECTNAME   

Tip: GitHub will provide a convenient link with the correct USERNAME and PROJECTNAME that you can copy and paste.

Fetch and Merge the TKLtemplate
'''''''''''''''''''''''''''''''
To copy the TKLtemplate, we'll add it as an upstream source.

    git remote add upstream https://github.com/Dude4Linux/TKLtemplate.git
    git fetch upstream
    git merge upstream/master

Replace template README.rst
'''''''''''''''''''''''''''

    mv README.app README.rst

Edit README.rst and changelog
'''''''''''''''''''''''''''''

Edit the files, replacing all references to #MyApp#, #Author#, #email# and #date# with the appropriate values.

Commit and Push the changes
''''''''''''''''''

    git add .
    git commit -m "initial commit"
    git push -u origin master





-------------------------------------------

.. _GitHub: https://github.com
.. _Guidelines: http://github.com/turnkeylinux/tracker/blob/master/GITFLOW.rst
