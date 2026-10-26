# Nintendo Clients
> :warning: This package talks to Nintendo's servers. Using it is at your own risk. Make sure that you know what you are doing.

This package implements a client for the 3DS and Wii U account and friend servers. It contains the `nex` friend protocol together with the PRUDP, RMC and kerberos layers that it depends on. The code is kept as a reference implementation for porting the friend code to other languages.

For talk about research, feel free to join the [Discord server](https://discord.gg/x8np6Hhxwk) or open a [discussion](https://github.com/kinnay/NintendoClients/discussions) on GitHub.

### Installation
This package requires Python 3.8 or later and can be installed with pip: `pip install nintendoclients`. This package uses [semantic versioning](https://semver.org/).

### Documentation
* [Nintendo's servers and protocols](https://github.com/Kinnay/NintendoClients/wiki)
* [The classes and functions in this package](https://nintendoclients.readthedocs.io)

### Example scripts
* **3ds/**
    * **friends.py:** Changes your comment to 'Hello World'.
    <br><br>
* **wiiu/**
    * **friends.py:** Requests your friend list, incoming and outgoing friend requests, and blacklist.
    <br><br>
* **custom/**
    * **server.py:** Shows how to create a simple game server with both an authentication server and a secure server.
    * **server_login.py:** Logs in on a game server and disconnects immediately. This can be used to test custom servers.

### Sponsorship
Consider becoming a [sponsor](https://github.com/sponsors/kinnay) if you would like to support this project.

If you become a sponsor, I will be able to spend more time on this project, which will lead to faster updates. In addition, you will be given priority for personal support and feature suggestions.
