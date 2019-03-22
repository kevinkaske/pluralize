# pluralize
A simple PHP lib to turn words into their plural form. Based on the rules from Rails pluralize.

## Install via composer
Installation of pluralize is through [composer](https://getcomposer.org).

To get started quickly, run the following command
```bash
composer require kevinkaske/pluralize
```
## Usage
```php
pluralize(single_string,number_int);
```

#### Example 1:
```php
$balloon_number = 1;

echo 'You have '.$balloon_number.' '.pluralize('balloon',$balloon_number).'!';
```
Would output ```You have 1 balloon!```

#### Example 2:
```php
$balloon_number = 2;

echo 'You have '.$balloon_number.' '.pluralize('balloon',$balloon_number).'!';
```
Would output ```You have 2 balloons!```
