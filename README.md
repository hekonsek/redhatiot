# Red Hat IoT

## Documentation

### Installation

In order to install redhatiot on CentOS 7.2, first install redhatiot command line:

    $ bash <(curl -sL https://goo.gl/gB2bk5)
    Installed redhatiot client into /usr/bin/redhatiot .

Then execute the following command, which starts the PaaS platform and deploys redhatiot services into it:

    redhatiot start

Start commands ensures that redhatiot has been started only once. If redhatiot is already running, execution of the the `start` command does nothing. 