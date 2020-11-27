Real estate project
===================

Composer project for starting a new real estate website.

Requirements
------------

- Composer
- Lando

Installation
------------

Download the project using Composer.

```
$ composer create-project --stability=dev code-lab-eu/real-estate-project my-real-estate-project
```

Start the web server Docker containers using Lando.

```
$ cd my-real-estate-project
$ lando start
```

Then navigate to https://real-estate-project.lndo.site/ and follow the
installation instructions. Use the following credentials for the database:

- Database type: MySQL
- Database name: drupal9
- Database username: drupal9
- Database password: drupal9

Advanced options:

- Host: database
- Port number: 3306
