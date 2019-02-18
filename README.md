# PHPCompabilityCheck

This small repository is a collection of code joined into a simple composer.json for easier installation.

```
$ git clone https://github.com/tomasnorre/PHPCompabilityCheck.git
$ cd PHPCompabilityCheck
$ composer update
$ composer install
# Include your new bin-dir to your $PATH
$ export PATH=~/.composer/vendor/bin:$PATH
# Verify that "PhpCompatibility" is installed and phpcs is available:
$ phpcs -i
# Run the tests:
$ phpcs --standard=PHPCompatibility --runtime-set testVersion 5.3 /path/to/your/code/
$ phpcs --standard=PHPCompatibility --runtime-set testVersion 5.6 /path/to/your/code/
```

You can get more info here, that's where I got the inspiration from:
[https://github.com/wimg/PHPCompatibility](https://github.com/wimg/PHPCompatibility)
[http://techblog.wimgodden.be/2013/10/15/phpcompatibility-update/](http://techblog.wimgodden.be/2013/10/15/phpcompatibility-update/)
[http://techblog.wimgodden.be/tag/codesniffer/](http://techblog.wimgodden.be/tag/codesniffer/)
