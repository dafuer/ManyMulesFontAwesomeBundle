Symfony2 Font Awesome Bundle
=======================

## Current Version

Font Awesome 2012-03-09

## Installation

### Add bundle to your vendor folder

    git submodule add git://github.com/ManyMules/ManyMulesFontAwesomeBundle.git vendor/bundles/ManyMules/Bundle/FontAwesomeBundle

### Add bundle to your application kernel

    // app/AppKernel.php
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new ManyMules\Bundle\FontAwesomeBundle\ManyMulesFontAwesomeBundle(),
            // ...
        );
    }

### Add ManyMules bundles folder to autoload

    // app/autoload.php
    $loader->registerNamespaces(array(
        ...
        'ManyMules\Bundle'               => __DIR__.'/../vendor/bundles',
        ...
    ));

Licenses
--------
Refer to the source code of the included files for license information

References
----------
[1]: http://fortawesome.github.com/Font-Awesome/
[2]: http://symfony.com