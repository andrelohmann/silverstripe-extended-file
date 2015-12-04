# silverstripe extended file

## Maintainers

 * Andre Lohmann (Nickname: andrelohmann)
  <lohmann dot andre at googlemail dot com>

## Requirements

Silverstripe 3.2.x

## Introduction

This module extends the File class with a load method, tha allows to create file objects from path.

## Usage

```php
$File = new File();
$File->load(FILE_PATH, TARGET_PATH);
```
