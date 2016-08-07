# linebot

a simple line bot api .

## Install

```
$ composer require ateliee/linebot:dev-master
```

## Usage

```
$bot = Ateliee\LineApi("<Channel ID>", "<Channel Secret>", "<Channel MID>", "<Endpoint URL>");
$bot->isValid(); // true only if signature was valid.
$bot->sendText("<to>", "<text>"); // send text message.
$bot->postEvents($events);
```
