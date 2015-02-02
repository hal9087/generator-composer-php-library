# <%= packageName %>
---------------------------------

<%= packageDescription %>

## Code Example

```
<?php

require_once "vendor/autoload.php";

// TODO

```

...To see more examples take a look into tests folder.


## Motivation

...

## Installation

```
$ git clone <project_repo>
$ cd <project_folder>
$ composer install
```

## API Reference

...TODO...

## Tests

if you have phpunit installed globally

```
$ phpunit 
```

or use the locally installed version

```
$ vendor/bin/phpunit
```

### Code analysis tools

***lint/checkstyle*** with phpcs:

```
$ composer phpcs
```

***mess detector*** with phpmd:

```
$ composer phpmd
```

***copy & paste detector*** with phpcpd:

```
$ composer phpcpd
```

***phpunit, lint, mess detector*** in one command:

```
$ composer test
```



## CI

A simple ci bash script exists under bin folder

```
$ bin/ci.sh
```


## License

MIT
