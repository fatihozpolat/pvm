# PVM: PHP Version Manager

## What is PVM?

PVM: allows you to easily download and install PHP for Windows operating system and quickly switch between PHP versions.

## How to use PVM?

### Install

```bash
$ npm install -g phpversionmanager
````

Add the `%PHP_SYMLINK%` variable to the **PATH**

### Usage

```bash
$ pvm install 7.4
$ pvm use 7.4
$ php -v
```

The above command will install PHP 7.4 and set it as the default version.

### for more information

```bash
$ pvm --help
```