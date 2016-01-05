# silverstripe extended file

## Maintainers

 * Andre Lohmann (Nickname: andrelohmann)
  <lohmann dot andre at googlemail dot com>

## Requirements

Silverstripe 3.2.x

## Introduction

This module extends the File class with a load method, that allows to create file objects from path and a CloudURL Method, that allows to use a thirdparty CDN Domain for all Files.

## Usage

```php
// Load from File
$File = new File();
$File->load(FILE_PATH, TARGET_PATH);

// use CDN URL
Config::inst()->update('ExtendedFile', 'cloud_url', YOUR_CDN_DOMAIN);
echo $File->getCloudURL();
```
