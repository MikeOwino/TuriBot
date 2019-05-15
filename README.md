# TuriBot
> TuriBot is a simple way to communicate with Telegram APIs in PHP

[![Latest Stable Version](https://poser.pugx.org/davtur19/turibot/v/stable)](https://packagist.org/packages/davtur19/turibot)
[![Total Downloads](https://poser.pugx.org/davtur19/turibot/downloads)](https://packagist.org/packages/davtur19/turibot)
[![License](https://poser.pugx.org/davtur19/turibot/license)](https://packagist.org/packages/davtur19/turibot)

## Requirements
PHP 7.1 or higher with curl extension

## Installation
```sh
composer require davtur19/turibot
```

## Usage
- Look at the examples ([webhook.php](https://github.com/davtur19/TuriBot/blob/master/examples/webhook.php) and [getUpdates.php](https://github.com/davtur19/TuriBot/blob/master/examples/getUpdates.php)), it's very simple if you know PHP and OOP
- All methods have the parameters in the same order as the [BotAPIs](https://core.telegram.org/bots/api#available-methods)
- The `reply_markup` parameters already have a json_encode in the functions, you just need to pass arrays

## Contributors
- [andrew-ld](https://github.com/andrew-ld)