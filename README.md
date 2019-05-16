Enum interface
===================

This document describes a common interface for registry enum class.

The goal set by `EnumInterface` is to standardize how frameworks and libraries make use of a
enum.

## 1. Specification
-----------------
- The `Wakeapp\Psr\Enum\EnumInterface` not exposes methods.


## 2. Interfaces
-------------
```php
<?php
namespace App;

use Wakeapp\Psr\Enum\EnumInterface;

/**
 * Describes the interface of a enum.
 */
class GenderEnum implements EnumInterface
{
    const MALE = 'Male';
    const FEMALE = 'Female';
}
```
