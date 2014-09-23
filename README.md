tomcat_bin
=======
tomcat start/stop/status/restart scripts for Linux


Install
-------
1. Control tomcat by scripts.

Modify tomcat.config: change running_user and tomcat_home for yourself.

2. Control tomcat as a Linux service.

Modify tomcat_running_home_dir in tomcat.


Usage
-------
cd tomcat_bin

./start_tomcat.sh     # start tomcat

./stop_tomcat.sh      # stop tomcat

./status_tomcat.sh    # get tomcat status

./restart_tomcat.sh   # restart tomcat


or

sudo service tomcat start/stop/status/restart

