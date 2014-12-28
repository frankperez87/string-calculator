# String Calculator
This allows you to sum up the numbers in a string.
- translates an empty string into zero
- finds the sum of one number
- finds the sum of two numbers
- finds the sum of any amount of numbers
- disallows negative numbers
- ignores any number that is one thousand or greater
- allows for new line delimeters

### Example:
```php
<?php

require 'vendor/autoload.php';

$calculator = new StringCalculator();

$sum = $calculator->add("10,20,30"); // Returns the sum of 60
```