# Awesome code [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Code samples from my collection** *new*

Code samples by me, from time 2 time I will add samples here.

Table of contents

* [PHP](#PHP)
* [Python](#Python)

* [License](#License)


## PHP

### YAML: add include ability

see [parsedown-user-styles](https://github.com/walter-a-jablonowski/parsedown-user-styles)

### YAML: Save SQL or Functions in YML

```yaml
ANY_KEY: |
  function() {
    
    // my PHP code

    return ...;
  }
```

run like

```php
eval("\$func = $yml[$key];");
$func();

// or 

($yml[$key])();
```

### Simple conditions in yml

```yaml
"@if SPECIAL_STRING":
  ANY_KEY_: ANY_VALUE
```

Just solve hard coded

```php
if( $key == '@if SPECIAL_STRING')
  // ...
```


## Python


## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/)


[Privacy](https://walter-a-jablonowski.github.io/privacy.html) | [Legal](https://walter-a-jablonowski.github.io/imprint.html)
