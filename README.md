# phpBB Camo SSL Image Proxy Extension

## This Extension is obsolete, replaced by https://github.com/v12mike/imageredirect

This is the repository for the development of the phpBB Camo SSL Image Proxy Extension.

## Quick Install
You can install this on the latest release of phpBB 3.1 by following the steps below:

1. In the `ext` directory of your phpBB board, create a new directory named `phpbb` (if it does not already exist) and navigate to it
1. `git clone git@github.com:phpbb-extensions/camo-ssl-image-proxy.git`
1. Navigate in the ACP to `Customise -> Manage extensions`.
1. Look for `Camo SSL Image Proxy` under the Disabled Extensions list, and click its `Enable` link.
1. Navigate in the ACP to 'Extensions -> Camo SSL Image Proxy -> Configure'.
1. Enter the proxy address (without protocol specifier or trailing /) e.g. mydomain.com/camo
1. Enter the camo API key (as applicable)
1. Add at least your sites domain(s) to the Directly Mapped Domains list (without protocol specifier or trailing /) e.g. mydomain.com
1. Ensure that 'Camo Mode' is selected and that 'Image Proxy Enable' is selected

Please note, this requires [Camo](https://github.com/atmos/camo) to have been setup previously.

## Support

* Report bugs and other issues to our [Issue Tracker](https://github.com/phpbb-extensions/camo-ssl-image-proxy/issues).

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

## Todo

* Add some sort of html tag to the image so that a user can access the original link.
* Add optional logging facility
