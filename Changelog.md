Changelog
=========

### 1.2.2
* Changed TreeBuilder creation, in Configuration::getConfigTreeBuilder to support Symfony 4.4. Remove deprecation messages "A tree builder without a root node is deprecated since Symfony 4.2 and will not be supported anymore in 5.0." and "The "Symfony\Component\Config\Definition\Builder\TreeBuilder::root()" method called for the "sc_expo_notifications" configuration is deprecated since Symfony 4.3, pass the root name to the constructor instead."

### 1.2.1

* Changed `sendNotificationHttp` and `sendNotificationsHttp` function of `Manager/NotificationManager.php` to be public accessible. Thanks to chriskaya!

### 1.2.0

* Updated dependencies for Symfony 4. Thanks to chriskaya!

### 1.1.0

* eightpoints/guzzle-bundle dependency updated to "^6.0". Thanks to stingus!

# 1.0.1

* Composer configuration updated.

* Readme updated since packagist is now set up.

# 1.0.0

* Initial release.

* All functions working.

* Configuration added (optional).

* Comments added.

### Pre-Release

* Basic functionality improved. Eased the usage overall.

* Composer setup to make bundle reusable.

* Basic project setup.
