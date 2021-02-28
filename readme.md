# Laravel Factory Converter

This package allows to easily convert your 'classic' model factories to the Laravel version 8 class style.

## Requirements

* PHP 7.4
* Your models are in the `App` namespace (`app` directory)
* There is no namespace defined in your seeders
* Start without any changes in your repository (make a backup if you don't use version control)

## Installation

```
composer global require rdh/laravel-factory-converter:dev-master
```

## Usage

**!! Your code will be PSR-2 formatted**

Make sure that your global composer bin directory is in your `$PATH`.
Find out where it is with:

```
composer global config bin-dir --absolute
```

Run the following commands for your project:

```
cd your-project
laravel-factory-converter
```

## Options

Check `laravel-factory-converter --help` for all options
