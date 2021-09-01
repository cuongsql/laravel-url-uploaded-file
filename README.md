Read the full post in my blog: https://cuongsql.com

## Installation

You can install the package via composer:

```bash
composer require cuongsql/laravel-url-uploaded-file
```

## Usage

``` php
use Cuongsql\UrlUploadedFile\UrlUploadedFile;

$file = UrlUploadedFile::createFromUrl('https://cuongsql.com/logo.png');
```

Now, because `UrlUploadedFile` extends `UploadedFile`, you can [store](https://laravel.com/docs/8.x/requests#storing-uploaded-files) it, get its [path and extension](https://laravel.com/docs/8.x/requests#storing-uploaded-files) and use `UploadedFile`'s functionality with it.

## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.
