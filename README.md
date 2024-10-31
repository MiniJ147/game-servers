# Game-Servers

## What is this about?

Game servers is a practice project developed in Go. The goal of this project is to simulate an auto-scaling game server system with TCP.  

The project will consist of **one central server** and **many game servers**.  

## Central Server
This server will act as the loader balancer and manager of all game servers.  

### Responsibilities include:  
- **Creating** and **Deleting** Game servers
- Managing connections between player and game servers
- Acting as a proxy and load balancer for game servers
- handling connection authenication

## Game Server
This server will be more of a simulation than anything as I don't have a real game to program the logic behind it. So, it will more act as a lobby which manages who can connect and who those connections are.

**TLDR:** a lobby should act as a simple chat server.

### Responsibilities include:
- Accepting and Rejecting incoming conncetions
- Allowing for players to send messages between each other

## Credits
inspired by: <a href="https://www.youtube.com/watch?v=qpu_iOGYC-g&ab_channel=TheVimeagen"> The Primeagen</a>

Built and developed with my live reloader written in this <a href="https://github.com/MiniJ147/miniloader">repo</a>

Note: this is subject to change and I am likely to add sqlc to the program inside of in memory storage. Also, the design between the Central Server and Game Server will change as I plan and develop this project further.