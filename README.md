# Custom Nova Tabs

This package provides custom tabs functionality for Laravel Nova.

## Installation

You can install the package via composer:

```bash
composer require webdeva/customnova-tabs
```

## Usage

```php
use Webdeva\CustomNovaTabs\CustomNovaTabs;

$customNovaTabs = new CustomNovaTabs();
$tab = $customNovaTabs->createTab('My Custom Tab', [
    // Add your Nova fields here
]);
```

## Testing

```bash
composer test
```

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
