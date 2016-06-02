# Skeleton (For plugins)

## Usage
* Pick the type of plugin you want to make, remove the others.
* Fix the SkeletonServiceProvider.php file to include your plugin
* Rename stuff from skeleton to what your plugin is called
* Fix composer.json
* Include in bot

## Install

In your main sovereign bot install, run this:
```
composer require sovereignbot/plugin-skeleton
```

Add the youtube-player service provider to your config file:
```
$config['serviceProviders'] = [
    ... 
    Sovereign\Service\SkeletonServiceProvider::class
];
```
And Restart Sovereign!
