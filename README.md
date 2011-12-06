A simple script for git to working with Teamcity and subversion server.

Prerequisition
====

> Download the tcc.jar from the "My Settings & Tools" > "TeamCity Tools" side panel > "Command Line Remote Run" to any directory.

> http://confluence.jetbrains.net/display/TW/Command+Line+Remote+Run+Tool

Configuraiton
====

* Update tcc_jar, tc_user, tc_password, tc_server in tc.py.

* Update configure_mapping.

* Run below command.

    git config --global alias.tc \\!/home/neil/workspace/teamcity/util/tc.py 

  Note: update file path

Usage
====

  Run below command in git-svn enabled respository.
 
    $ git tc
