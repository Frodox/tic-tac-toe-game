# Tic Tac Toe game

*version*: 1.1

It's simple, client-server (via INET-stream-sockets) game with gui-client on GTK2.

There are console and GUI versions of client.

**Requirements**:

* python >= 2.7
* gtk >= 2.16


## How to play

### Local

1. Clone repo ( `git clone https://github.com/Frodox/tic-tac-toe-game.git` )
2. Start server ( `./tic-tac-server.py` )
3. Start client console or gui version ( `./tic-tac-client.py` )
4. Enjoy.


### With friends

1. Clone repo
2. Player_1 starts a server in multiplayer mode on some *port*, like `./tic-tac-server.py -m -p 7777` (default port -- 64501); there is only console version of server
3. Player_2 starts a console/gui client like `./tic-tac-client.py --host <player 1 IP> --port PORT`
4. Enjoy



License: GPL v3
