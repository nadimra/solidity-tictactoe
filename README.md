# Decentalised Tic-Tac-Toe

Create a decentralized application for a tic-tac-toe game.

## Instructions
You can run `docker build -t tic-tac-toe .` to build the tic-tac-toe docker image.

Prerequisite: please [install docker](https://docs.docker.com/desktop/) on your system.

To set up and play your tic-tac-toe game, you can:

1. start the ganache test chain

`docker run -p 8545:8545 -d trufflesuite/ganache-cli:latest -g 0`

2. start the web server

`docker run -p 8080:8080 -d tic-tac-toe`

3. open `http://localhost:8080/` in two separate web browsers with each a separate Metamask installed, and enjoy the game. On Chrome you can create **two different users** and install Metamask in each. You'll need to configure Metamask to connect to your local chain as well (which is not graded but we leave this up to you as part of the exercise for your own testing).
