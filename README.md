# grav-tawkto-plugin
A simple tawk.to plugin for grav websites.

This is [Grav CMS](http://getgrav.org) plugin that helps you implement [tawk.to Live Chat](https://tawk.to).

Code is basically a modified version from Michele Palmieri's code base [view here](https://github.com/MichelePalmieri/grav-piwik-plugin)
# Installation

Installing the Tawk.to plugin can be done in one of two ways.

## GPM Installation (Preferred)

COMING SOON

The simplest way to install this plugin is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install tawkto

This will install the tawk.to plugin into your `/user/plugins` directory within Grav. Its files can be found under `/your/site/grav/user/plugins/tawkto`.

## Manual Installation

To install this plugin, just [download](https://github.com/uptimemania/grav-tawkto-plugin/archive/master.zip) the zip version of this repository and unzip it under `/your/site/grav/user/plugins`. Then, rename the folder to `tawkto`.

You should now have all the plugin files under

    /your/site/grav/user/plugins/tawkto

# Config Defaults

```
enabled: true
siteId: 0
```

If you need to change any value, then the best process is to copy the [tawkto.yaml](tawkto.yaml) file into your `users/config/plugins/` folder (create it if it doesn't exist), and then modify there. This will override the default settings.

# Usage
1. Copy the *ID* *URL* and insert it to the configuration of this plugin.
