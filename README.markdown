Puppet CloudPack
================

Puppet Plugins for managing in the cloud.

This module requires Puppet 2.7.0 or later.

Getting Started
===============

 * [Getting Started With CloudPack](http://docs.puppetlabs.com/guides/cloud_pack_getting_started.html)

Required Gems
=============

 * guid (tested with 0.1.1)
 * fog (0.7.2)

AMI Image
---------

A good image to get started with is *ami-90f607f9* named
"RightImage\_CentOS\_5.4\_i386\_v5.6.8.1"

Building the Module
===================

The [Puppet Module Tool](https://github.com/puppetlabs/puppet-module-tool) may
be used to build an installable package of this Puppet Module.

    $ puppet-module build
    ======================================================
    Building /Users/jeff/src/modules/cloudpack for release
    ------------------------------------------------------
    Done. Built: pkg/puppetlabs-cloudpack-0.0.1.tar.gz

To install the packaged module:

    $ cd <modulepath> (usually /etc/puppet/modules)
    $ puppet-module install ~/src/modules/cloudpack/pkg/puppetlabs-cloudpack-0.0.1.tar.gz
    Installed "puppetlabs-cloudpack-0.0.1" into directory: cloudpack
