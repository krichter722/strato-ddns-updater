# Strato DDNS Updater
A python script which allows you to update your Dynamic DNS information for a strato domain supporting this feature. It has been written due to the fact that many well-known DDNS clients, like `dyndns`, `ddclient` and `ipcheck` support `dyndns.org` only and don't allow customization of the URL path and query. An `upstart` script is installed together with the binaries with `sudo python setup.py install`.

## Installation
Install the Cheetah templating engine (e.g. with `sudo apt-get update && sudo apt-get install python-cheetah` on Ubuntu 14.10) and run `sudo python setup.py install`.
