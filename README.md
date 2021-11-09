# Ace

This is a command line bootstrapper for the [Horizon Framework](https://github.com/baileyherbert/horizon). You can
install this package globally to easily access the command interface for your application.

## Installation

```bash
composer global require baileyherbert/ace
```

## Notes

This package only contains a binary that traverses from the current directory upward and locates your application root,
then invokes the application in console mode. The version of the command line tool and the commands within it will
match those installed in your application.

You can find the source code for all official commands in the official repository:
https://github.com/baileyherbert/horizon/tree/master/src/Ace
