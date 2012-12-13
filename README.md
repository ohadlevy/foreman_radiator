# foreman_radiator

This is a rails engine that allows users to view from within Foreman (https://github.com/theforeman/foreman) the radiator page found in Puppet Dashboard (https://github.com/puppetlabs/puppet-dashboard). The HTML and CSS has been taken directly from the Puppet Dashboard project.

![Image](https://raw.github.com/isratrade/foreman_radiator/master/screenshot_radiator.jpg)

# Installation:

1) Add the gem. Add a file (ex. radiator.rb) under the folder /bundler.d in your foreman installation and add the following line.

gem 'foreman_radiator', :git => "https://github.com/isratrade/foreman_radiator.git"

2) Run "bundle" as the your foreman user (important)

3) Go to path "http://yourforeman/radiator"


# Copyright

Copyright (c) 2012 Joseph Mitchell Magen. See LICENSE.txt for
further details.

