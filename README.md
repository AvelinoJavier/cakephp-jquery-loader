# JqueryLoader plugin for CakePHP
Plugin that injects Jquery V3.6.0 via html helper element.

## Installation
```
composer require avelinojavier/cakephp-jquery-loader
```

## Usage
You can paste this code in your default layout header.
```
<?= $this->element('JqueryLoader.load') ?>
```