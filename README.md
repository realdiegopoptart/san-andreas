# San Andreas
A Grand Theft Auto San Andreas themed discord bot. *Inspired by realdiegopoptart's San Andreas Toolkit bot*

### NOTICE: `/radio unpause & /voice pause` **WILL NOT** work until Discord-PHP merges pull requests [#978](https://github.com/discord-php/DiscordPHP/pull/978) & [#979](https://github.com/discord-php/DiscordPHP/pull/979) to `dev-master`

### NOTICE: `/radio play song:` option autocomplete will not work until pull request [#980](https://github.com/discord-php/DiscordPHP/pull/980)

# Prerequisites #

* PHP 8.1
* FFmpeg
* PHP Sodium Extension

# Setup

`git clone https://github.com/CommandString/san-andreas-toolkit`

`composer install`

copy env.example.json to env.json

Add your token to env.json

`php command save Radio`

Then start the bot with `php index.php`

# Adding additional features to the bot

If you want to add your own features to this bot I would highly recommend you read [Discord-PHP-Design-Structure](https://github.com/CommandString/DiscordPHP-Design-Structure) which is what this bot uses as a boilerplate. If you have any questions feel free to join https://discord.gg/TgrcSkuDtQ my discord server and ask there or dm me directly at `Command_String#6538`
