Online Presentations 2015 
-------------------------
A set of presnetation from 2015 you can host online.


Install with one click
----------------------
[![Click to  install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to  install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.4&initial_git_url=https://github.com/eschabell/openshift-preso-2015.git&name=presos)


Manual setup on OpenShift
-------------------------
Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create presos -t php-5.4 --from-code git://github.com/eschabell/openshift-preso-2015.git

That's it, you can now start your workshop at:

    http://presos-$your_domain.rhcloud.com

![Cover Slide](https://raw.githubusercontent.com/eschabell/openshift-presos-2015/master/cover.png)
