# bsfc-server
bsfc-server is a simple shell & python tool group to download, setup and
run a BombSquad: [FuseCore](https://github.com/NST-Servers/fusecore) server.

Having to download and update your BombSquad server on each release might get a
little tedious, and having a toolchain for a server version that is outdated and
insecure is even more frustrating. The goal of BSFC is to tackle both issues and
make working with an up-to-date custom server as seamless as running a shell script.

## How to use:
* Clone this repository
  ```sh
  git clone https://github.com/NST-Servers/bsfc-server.git
  ```
* Run ``./update`` to start downloading the latest BombSquad server and fusecore releases.
* Edit the generated ``config.toml`` file to configure your server.
* Once you're done, execute ``./start`` to initialize your server.

That's it! You're now the proud owner of a BombSquad: FuseCore server!
