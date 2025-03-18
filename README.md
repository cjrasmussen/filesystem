# Image

Simple functions for interacting with the file system.

## Usage

```php
use cjrasmussen\FileSystem\FileSystem;

$indexFiles = Filesystem::scanDirRecursive('/var/www/html/', 'index.html');
```

## Installation

Simply add a dependency on cjrasmussen/filesystem to your composer.json file if you use [Composer](https://getcomposer.org/) to manage the dependencies of your project:

```sh
composer require cjrasmussen/filesystem
```

Although it's recommended to use Composer, you can actually include the file(s) any way you want.


## License

FileSystem is [MIT](http://opensource.org/licenses/MIT) licensed.