# Yii2 Switch

A simple switch with a low waste of resources and fast response time.

## Installation

Install the package with composer by executing the command:

```bash
composer require "skepticspriggan/yii2-switch:*"
```

## Usage

```php
<?php
use SkepticSpriggan\Switch;

echo Switch::widget([
    'label' => 'Light',
    'checked' => true,
    'onUrl' => Url::to(['light/on']),
    'offUrl' => Url::to(['light/off']),
]);
?>
```
