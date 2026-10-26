
## Welcome to NintendoClients

This package lets you communicate with the 3DS and Wii U account and friend servers. For documentation about the servers and protocols click [here](https://github.com/kinnay/nintendo/wiki).

* [Features](#features)
* [Contributing](#contributing)
* [API Reference](#api-reference)
* [Changelog](changelog.md)

## Features
This package is able to do everything that's required to access a game server. It also provides a framework to host your own game servers. For example scripts, check out the [github repository](https://github.com/kinnay/nintendo). The following servers are currently supported:

* 3DS:
	* Friend server (`nex`)
	* https://nasc.nintendowifi.net
* Wii U:
	* Friend server (`nex`)
	* https://account.nintendo.net

## Contributing
Feel free to open a pull request or issue on [github](https://github.com/kinnay/nintendo). If you open a pull request, please try to follow the current code style as much as possible, and consider writing a test for new features and bug fixes.

## API Reference

* nex
	* [authentication](reference/nex/authentication.md)
	* [backend](reference/nex/backend.md)
	* [common](reference/nex/common.md)
	* [errors](reference/nex/errors.md)
	* [friends](reference/nex/friends.md)
	* [kerberos](reference/nex/kerberos.md)
	* [notification](reference/nex/notification.md)
	* [prudp](reference/nex/prudp.md)
	* [rmc](reference/nex/rmc.md)
	* [settings](reference/nex/settings.md)
	* [streams](reference/nex/streams.md)
* [nasc](reference/nasc.md)
* [nnas](reference/nnas.md)
