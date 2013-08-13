OpenShift Python 2.7 Addon Cartridge
========================================

This git repository is an addon cartridge to help you get
started with using Python 2.7.3 on Red Hat's OpenShift PaaS.

It is essentially a stripped down version of the OpenShift Community Python 2.7 Cartridge
with the web framework removed so it can be used as an addon cartridge on an app that
already has an existing web framework cartridge .


ssh/virtualenv Caveats
----------------------
When you ssh into your app/gear, you will need to source in a script to setup the library paths and activate the virtualenv python 2.7 is installed under.

    ssh  $guid@$app-$ns.rhcloud.com
    rhcsh> source python-2.7/activate_virtenv

.    
.    
... And last but not least, enjoy your flight ... http://xkcd.com/353/


