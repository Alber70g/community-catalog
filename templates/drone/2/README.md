# Drone

### Info:

This template creates an instance of Drone CI server 0.5 along with one agent to perform the builds.

### Usage:

Select the Drone template from the catalog. Provide the following information:

You can only have true for one Remote (git source). The rest must be set to false.  Once you've selected the remote
you must set the rest of the options for that remote. If you don't select a database option you'll need to uprade
the Drone service to mount the conatiner volume /var/lib/drone/ to save build info. ie. /drone/:/var/lib/drone/


See [Drone documentation](http://readme.drone.io/) for complete information.