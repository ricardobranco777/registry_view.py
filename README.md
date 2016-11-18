# registry_view.py
Script to visualize the contents of a Docker Registry v2 using PyCurl

Usage: registry_view.py [OPTIONS]... REGISTRY[:PORT][/REPOSITORY[:TAG]]
Options:
	-c, --cert CERT		Client certificate file name
	-k, --key  KEY		Client private key file name
	-p, --pass PASS		Pass phrase for the private key
	-u, --user USER[:PASS]	Server user and password (for HTTP Basic authentication)
        -v, --verbose		Be verbose. May be specified multiple times

Note: Default port is 443. You must specify "http://..." if running on plain HTTP.
