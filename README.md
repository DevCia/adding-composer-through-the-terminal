# Adding composer through the terminal

```PROMPT
composer init
```

```PROMPT
Package name (<vendor>/<name>): luizpaulogroup/example
```

```PROMPT
Description []: Adding composer through the terminal
```

```PROMPT
Author: luizpaulogroup <email@gmail.com>
```

```PROMPT
Minimum Stability []: stable
```

### you can skip this step just below, pressing enter
```PROMPT
Package Type...
```

### Next
```PROMPT
License []: MIT
```

### you can skip this step just below, pressing enter
```PROMPT
Would you like to define your dependencies (require)...
```
```PROMPT
Would you like to define your dependencies (require-dev)...
```

### Next
```PROMPT
Do you confirm generation [yes]? yes
```

```PROMPT
composer update
```

```PROMPT
composer install
```

## Command to add package

### packagist

## You can be accessing the website https://packagist.org/

```PROMPT
composer riquired package_name
```

## The composer.json file will look like this
```JSON
{
    "name": "luizpaulogroup/example",
    "description": "Adding composer through the terminal",
    "license": "MIT",
    "authors": [
        {
            "name": "luizpaulogroup",
            "email": "email@gmail.com"
        }
    ],
    "minimum-stability": "stable",
    "require": {

    }
}
```
