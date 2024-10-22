## Scraper

A scraper script which scrapes data from a given link and save data to a JSON file.

## Prerequisite

I'm using Xampp,Composer for setup.

- PHP version 8.2

## Installation

Clone the repo locally:

```sh
git clone https://github.com/goutamwms/scraper.git
cd scraper
```

Install PHP dependencies:

```sh
composer install
```

You're ready to go!

## Run the script

To run the scraper, run:

```sh
 php src/Scrape.php
```

## Running tests

To run the tests, run:

```sh
composer test
```

## Check code vulnerability

To run static analysis tool phpstan, run:

```sh
composer analyse
```

## Check code style/format

To run pint, run:

```sh
composer fix
```
