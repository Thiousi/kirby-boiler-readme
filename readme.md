# Kirby Boiler Readme

*Version 1.0*

Write a description here. It should be short and sweet about what the plugin does. If you can, add an animated gif or screenshot. It will probably make more people use your plugin.

## Installation

### [Kirby CLI](https://github.com/getkirby/cli)

Run this command:

```
kirby plugin:install github-name/kirby-your-plugin
```

### Manually

Add the folder `kirby-your-plugin` into `/site/plugins/`.

## Setup

### 1. Blueprint

If your plugin requires a blueprint setup, this may be a good start:

```
fields:
  yourfield:
    title: Your Field
    type: yourfield
```

### 2. Add JS to your footer

If your plugin uses assets, this may be a good start:

```php
echo js('assets/plugins/kirby-your-plugin/js/script.js');
```

## Usage

Describe how to use this plugin. Text, images, videos etc is good here.

## Options

### A plugin option

Describe the option and always set the second argument as the default.

```
c::set('plugin.your.plugin.option', 'Default value');
```

## Changelog

**1.1**

- Add the items in a descending order 

**1.0**

- Some important change
- Initial release

## Requirements

Kirby 2.0

## License

MIT