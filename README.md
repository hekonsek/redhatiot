# Red Hat IoT

## Documentation

### Installation

In order to install redhatiot on CentOS 7.2, first install redhatiot command line:

    $ bash <(curl -sL https://goo.gl/Kl8AId)
    redhatiot client has been installed into /usr/bin/redhatiot .

Then execute the following command, which starts the PaaS platform and deploys [standard redhatiot components](installation.md) into it:

    redhatiot start

Start commands ensures that redhatiot has been started only once. If redhatiot is already running, execution of the the `start` command does nothing.

Out of the box redhatiot installs and starts OpenShift PaaS and deploys the following components into it:
- MongoDB database
- [Keycloak](http://www.keycloak.org) server
- core services application