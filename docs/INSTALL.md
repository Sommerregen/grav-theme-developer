# [Installation and update guide][project]
[project]: https://github.com/sommerregen/grav-theme-developer

## Installation

Installing the `Developer` theme can be done in one of two ways. The GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

### GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line). From the root of your Grav install type:

    bin/gpm install developer

This will install the `Developer` theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/developer`.

### Manual Installation

To install this plugin, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `Developer`. You can find these files either on [GitHub](https://github.com/sommerregen/grav-plugin-developer) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/developer

>> NOTE: This theme is a modular component for Grav which requires [Grav](http://github.com/getgrav/grav) in order to operate.

## Updating

As development for `Developer` continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating `Developer` is easy, and can be done through Grav's GPM system, as well as manually.

### GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update developer

This command will check your Grav install to see if your `Developer` theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

#### Manual Update

Manually updating `Developer` is pretty simple. Here is what you will need to do to get this done:

  * Delete the `your/site/user/themes/developer` directory.
  * Download the new version of the `Developer` theme from either [GitHub](https://github.com/sommerregen/grav-plugin-developer) or [GetGrav.org](http://getgrav.org/downloads/themes).
  * Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `developer`.
  * Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

>> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.
