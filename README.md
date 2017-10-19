# Islandora BagIt Extension 

## Introduction

[Extenstion to Islandora BagIt](https://github.com/Islandora/islandora_bagit) allowing the storage of a Bag in a custom directory, instantiation from a Drush script, and providing a PID/timestamp for auditing


## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Tuque](https://github.com/islandora/tuque)
* [Scholars' Lab BagItPHP library](https://github.com/scholarslab/BagItPHP)
* [Archive_Tar](http://pear.php.net/package/Archive_Tar)
* [Libraries](https://drupal.org/project/libraries)
* [Bagit Islandora](https://github.com/Islandora/islandora_bagit)

## Installation

To install the Islandora BagIt module:

1. Unzip this module into your site's modules directory as you would any other contrib module.


## Configuration

See [Bagit Islandora](https://github.com/Islandora/islandora_bagit)


### Permissions and security

This module is intended for users who have a fairly high level of permissions on a Drupal site. Because the goal is to package up all or some of the datastreams in an Islandora object, users who can create and download Bags should have access to those datastreams. However, the module does check the current users' access to a datastream before adding it to the Bag.

## Documentation

See [Bagit Islandora](https://github.com/Islandora/islandora_bagit)


## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
