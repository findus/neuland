Script that automatically rewrites the routing table based on rules defined inside the script.
If a network device is attached/removed the script reruns and takes care of bringing the device up.

Current Features:
 - Traffic routing over specific network interfaces
 - Routing of UDP Packets over specific NIC

Right now everything is pretty hardcoded, I might rewrite it, so that rules could be placed
inside a config file, so that you dont have to manually edit the script file.
