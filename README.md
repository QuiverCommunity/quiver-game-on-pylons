# Introduction

This game is built by Quiver community to support Pylons community.

# How to build the game

We will build terminal game with great idea by forking LOUD game.

# Research for blockchainy game industry
https://www.quora.com/Why-do-people-love-Pokemon
Already existing games list can be found here
https://egamers.io/blockchain-games-list/

Here's alpha version of space fighting game that is similar to what I have described at the top.
https://www.csc-game.com/
There are top 4 great potential blockchain games
https://hackernoon.com/5-blockchain-games-that-you-need-to-know-about-lbu36gt
Most Anticipated Blockchain Games for 2020
https://www.blockchaingamer.biz/features/3283/most-anticipated-blockchain-games/
13 of the Best Blockchain Games (Updated for 2019)
https://blockexplorer.com/news/best-blockchain-games/
What Happened to Blockchain Gaming?
https://www.gamedesigning.org/gaming/blockchain/
I like classic style games like dog and cat 2d game, but these games are visually too crazy.
Checkout a blockchain game company
https://mythical.games/
Most of the game channels have discord and it's possible to track game status and users' feedback there
Blockchain game ideas on Reddit
https://www.reddit.com/r/gamedesign/comments/4u1i0f/looking_for_ideas_for_a_blockchainbased_game/

# Reference games that might be good to build from scratch (It's not blockchain, it would be better to get idea from existing blockchainy games)
https://github.com/fuhrmanator/melee-sim-js
Check for game idea "The Fantasy Trip Melee"
Verified: This is game where 3 characters participate in game and players can do fight, move, escape etc. Winners get bonus points.

https://boardgamegeek.com/boardgame/143884/machi-koro
Machi Koro is a fast-paced game for 2-4 players. Each player wants to develop the city on their own terms in order to complete all of the landmarks under construction faster than their rivals. On their turn, each player rolls one or two dice. If the sum of the dice rolled matches the number of a building that a player owns, they get the effect of that building; in some cases opponents will also benefit from your dice (just as you can benefit from theirs). Then, with money in hand a player can build a landmark or a new building, ideally adding to the wealth of their city on future turns. The first player to construct all of their landmarks wins!

https://github.com/nornagon/hf-mission-planner
High Frontier 4 All

https://boardgamegeek.com/boardgame/25669/qwirkle
Qwirkle

A game like Reigns might be cool said by Michael,
https://play.google.com/store/apps/details?id=com.devolver.reigns

Said by Reuven Podmazo
https://www.westeros.org/

# TODO research
Search for RPG games open-source and idea research
Search ideas for Board games, open-source research is done
Search for story games that can be done using delayed approach
Search for game development resources / companies. e.g. https://github.com/seiyria/awesome-boardgame-development
Search for turn-based strategy games
Search for great game winner dashboard, users will like to see the best players listing
Search for turn based survival games

# Games to build 
1. Build Warmax like game for easiest game prototype
http://wormax.io
It's a game that is derivated from a game called "slither".
Open sources to consider
https://github.com/iiegor/slither
https://github.com/crytic/slither
https://github.com/whxaxes/slither
https://github.com/Loonride/slither.io-clone
https://github.com/maxmx/slither
https://github.com/PlitherProject/Plither
https://github.com/dahquan/rattlesnake

Items and the users' score will be stored in Pylons system.
I will run socket.io server that connect users globally.

2. Build Cat vs Dog like game for another easier game
It's classic game, but there can be users who like to play.
Players can purchase Cat and Dogs and other great items.
And multiple players can do match online with their character.

*How to play Cat vs. Dog swf on MacOS*

Download [Elmedia player](https://mac.eltima.com/media-player.html) and install on MacOS.
Run the Elmedia player and drag and drop `catvsdog.swf`. That's all for how to run the game.

3. Build a first web based multi-player board game which is similar to stratego
http://www.stratego.com/
It's a game that is similar to what I have been playing when young on paper. (Elephant, Lion, Tiger, Rat etc.)
Open source to consider
https://github.com/benjaminkomen/stratego-frontend

Is it possible to implement this on Pylons system? Michael said it's not easy, consider doing it later when they support multiple players feature.

4. Build a "Legends of Andor" like game, a kind of board game
http://legendsofandor.com/
“Legends of Andor” is a cooperative board game for 2–4 heroes.
The idea is defeating the Andor region.

Open source to consider
https://github.com/Saphareas/Andor-Custom-Cards-Builder

5. Build a casino game 

Open source to consider
Web client for blockchain poker: https://github.com/acebusters/acebusters-frontend

https://github.com/Yaoir/VideoPoker-Go
A text-based video poker game - Go (Golang) version
Verified: Text based poker will be easy to make

6. Build a Galaxy Game

https://planets.nu
Galaxy Game where gamers can attack other planets etc and a player can purchase items to attack other planets or defend his/her planets.
Cosmos is a universe and this game idea might be great.
There can be a rule to calculate distance between planets.
Idea for calculating distance between planets
This is sample address
cosmos1jh78j6lkla83uvukyd24s33wu83ug3e394h0d3
This can be converted to 3D axis point
(1jh78j6lkla83uv, ukyd24s33w, u83ug3e394h0d3)

It's hard to attack a planet which is far away
He can put safe items there
Like diamond or something
And to conquer other world, he needs to travel
And the travel time could take 1-2 days
If he left to attack other planet, that planet does not have enough power to defeat other attacks
If possible, there can be a barrack to generate soldiers

# Rust video game

https://github.com/ozkriff/zoc
⬡ Zone of Control is a hexagonal turn-based strategy game written in Rust. [DISCONTINUED] https://ozkriff.itch.io/zoc

Verified. It's a kind of desktop turn-based board game written in rust. Reduce the health of tanks and soliders on every turn.

https://github.com/ozkriff/zemeroth
😠⚔️😈 A minimalistic 2D turn-based tactical game in Rust https://ozkriff.itch.io/zemeroth

Verified. It's a similar game to zoc (Zone of Control) game with different kind of monsters.

# Golang terminal games

https://github.com/topheman/gopher-ball
Video game made in golang, based on sdl2 bindings
Verified: Good use of sdl2 library but not useful for blockchain turn based game.

https://github.com/fiorix/cat-o-licious
Cat game written in Go
Verified: Good use of sdl2 library but not useful for blockchain turn based game.

https://github.com/tristangoossens/snake-go
Snake game made in Go! 🐍 https://tristangoossens.itch.io/snake-go
Verified: Good use of sdl2 library but not useful for blockchain turn based game.

https://github.com/zladovan/gorched
Gorched is terminal based game written in Go inspired by "The Mother of all games" Scorched Earth
Verified: Good terminal fill color library but not useful for blockchain turn based game.

https://github.com/austinov/gopher-game
gopher-game is a simple game in a terminal.
Verified: simiar to "Salt stealing game", I was doing when I was young but not blockchainy.

https://github.com/AppsComTr/Spaceship
Multiplayer game backend framework which is written with Golang

https://github.com/heroiclabs/nakama
Distributed server for social and realtime games and apps. https://heroiclabs.com

https://github.com/Terkwood/BUGOUT
AI-driven, Multiplayer Go/Weiqi/Baduk for the web 🐛🤖🦀♟

# Lua terminal game

https://github.com/rm-code/On-The-Roadside
A turn-based ASCII strategy game. https://rmcode.itch.io/on-the-roadside

# Javascript terminal games
https://github.com/Yaoir/VideoPoker-JavaScript
This is the JavaScript/Node.js version of videopoker.

https://github.com/wardbradt/cloudpoker
Node poker server using Redis, React, Webpack, Socket.io

https://github.com/walsh9/7drl2015
Chitinous Crooks - Retrieve the Jewel of Zot from the lobsterfolk. http://walsh9.github.io/7drl2015

# Golang video games

https://github.com/ginuerzh/poker
Texas Hold’em poker game h5+golang

https://github.com/campoy/flappy-gopher
The code for the Flappy Gopher episodes of #justforfunc http://youtube.com/c/

https://github.com/maxproske/games-with-go
A collection of small game-related projects built using Go and SDL2

https://github.com/fraenky8/go-snake
The Snake Game written in Go & SDL2

# Golang web game
https://github.com/azartpay/poker-10
Texas Hold’em poker game h5+golang

# Golang library
Poker library written in go (golang)


# Javascript video games
# Javascript terminal game
https://github.com/michelebucelli/node-taboo
Taboo game wiki https://en.wikipedia.org/wiki/Taboo_(game)
Usability: It's a word guessing game and if we build english word guessing game, this can be very interesting for learning english.

# Javascript web and electron game
https://github.com/chukwumaijem/ludo-game
Ludo game. Built with Reactjs. Made to work on the browser and Electron! 

https://github.com/monicanagent/cypherpoker.js
CypherPoker.JS is a complete, white label, peer-to-peer poker platform that incorporates a flexible and highly customizable web / desktop game client, powerful P2P communication capabilities, account management system with database integration and extensible API services, automated cryptocurrency and wallet functionality, and much more.

# Javascript web game
https://github.com/FaisalST32/minesweeper
MineSweeper
Usability: Can do multiplayer minesweeper or do it alone by giving time when click mouse or something

https://github.com/Eyap53/PlayThemAll
Chess is 

https://github.com/jacobgarcia/werewolf-brain
Ref. https://imgur.com/a/13ugp, https://en.wikipedia.org/wiki/Ultimate_Werewolf

https://github.com/AlecM33/Werewolf
An online, lobby-based multiplayer version of the social deception game Werewolf using Javascript and Websocket.

https://github.com/webdevian/pandemic
Ref. Javascript implementation of the board game Pandemic https://www.zmangames.com/en/games/pandemic/

https://github.com/1j01/board-game
Ref. http://1j01.github.io/board-game/
Usability: Animation for the balls are smooth and it can be useful later time

https://github.com/eranhirsch/scyther
Usability: Game font looks interesting

https://github.com/aprescott/tenuki
baduk game

https://github.com/byn9826/Warring-States-Epic
Chinese history game, 战国史话

https://ronhasson.github.io/ParaduxGame/
Board game, https://ronhasson.github.io/ParaduxGame/

https://github.com/karlb/nuclearchess
Nuclear Chess, http://www.karl.berlin/nuclearchess/#play

https://github.com/yishn/p2p-goban
Connect to peers and play/analyze on a shared Goban

https://github.com/arevi/Kill-Doctor-Lucky-Web-Port
A port of the classic "CheapAssGames" board game, Kill Doctor Lucky.

https://github.com/Maxsior/iota
board game IOTA

https://github.com/ianmah/botc-online
Online version of Blood on the Clocktower, https://bloodontheclocktower.com/buy

https://github.com/nientedidecente/elime
opensource clone of Earthcore: Shattered Elements https://elime.surge.sh/

https://github.com/igravitystudios/matchimals.fun
An animal matching puzzle card game, https://www.matchimals.fun/

https://github.com/mavend/octoboard
Collection of games that may help you and your friends kill the boredom of COVID19 quarantine

https://github.com/ShrimpCryptid/Secret-Hitler-Online
An online version of Secret Hitler, https://secret-hitler.online/

https://github.com/Oracle-of-the-Void/ootv-client
After Legend of the Five Rings was sold to Fantasy Flight at the end of 2015, Don Eisele (Author of the Oracle of the Void) has continued to fund and run the Oracle of the Void. He is currently working on revamping and coding the Oracle into a serverless cloud architecture on AWS. The new version will be faster, more resiliant (not running in Don's basement), and support other games., https://oracleofthevoid.com/

https://github.com/MichiBeutler/poker
Online Poker App

https://github.com/ProPanek/PlanningPoker
https://github.com/chrisandrews7/planning-poker.server
https://github.com/chrisandrews7/planning-poker.ui
Planning Poker/Scrum Poker using node.js and socket.io! https://planning-poker-uk.herokuapp.com/

https://github.com/jorgedonoso/reactivepoker.com
A collection of card game resources for beginners

https://github.com/unitehenry/poker.tech
Interactive Tabletop Poker

https://github.com/SFSU-CSC-667/term-project-poker
Online Poker - Texas Hold'em https://poker-games.herokuapp.com/


https://github.com/floatinghotpot/casino-server
🔥 An online poker game server powered by Redis, node.js and socket.io

https://github.com/RobertoDebarba/rise-of-shinigami
A 2D turn based RPG game made with RPG Maker MV platform

https://github.com/PetrHeinz/gods-play
PixiGame: God's Play is a multiplayer turn-based tactical game about mages trying to destroy each other. As they fight they spread havoc and destruction around themselves without considering consequences.

https://github.com/wyattdorn/flesh-n-bones
Turn-Based RPG - JavaScript

https://github.com/Greenheart/iso-conquest
A minimalistic, turn based strategy game with PvP and experimental AI

https://github.com/hervan/anaander
a turn-based strategy board game where all your units belong to a hive mind https://hervan.github.io/anaander/

https://github.com/sunDalik/Playable
This is literally playable https://sundalik.github.io/Playable/

https://github.com/fatcerberus/spectacles-i
The first installment of the Spectacles Saga, which follows Scott Starcross in his quest through Lucida as he attempts to defeat the Primus. Uses the Sphere engine!

https://github.com/sviridoff/tactical-rpg
An attempt to make `Fire Emblem Heroes` clone in Javascript https://sviridoff.github.io/tactical-rpg

https://github.com/tautvilas/epoh
Multiplayer turn-based browser strategy game http://www.epoh.io

https://github.com/rootasjey/cycles
A turn-based game system built with phaser

https://github.com/colyseus/colyseus
⚔ Multiplayer Game Server for Node.js https://colyseus.io

https://github.com/jaxankey/Virtual-Game-Table
A general-purpose, browser-based game table for casual games and rapid board game development.

https://github.com/yahiaetman/Go-Server
Go Server is a 2-Player Websockets Go Judging Server.

https://github.com/bast/go-game
Go game for the browser. https://bast.github.io/go-game/

https://github.com/kelleyvanevert/jsgo
Go on a torus, why not? :) http://kelleyvanevert.github.io/jsgo/

# Game Packages
https://github.com/MorelGames/morel-games-core
Common front-end components and logics for all Morel browser minigames.

https://github.com/LeonardoVal/ludorum.js
A board game framework, focused not on graphics or user interfaces, but on artificial players design, implementation and testing.
Sample board games built on ludorum.js
https://github.com/LeonardoVal/ludorum-game-chess.js
https://github.com/LeonardoVal/ludorum-game-colograph.js
https://github.com/LeonardoVal/ludorum-game-connect4.js
https://github.com/LeonardoVal/ludorum-gamepack.js
https://github.com/LeonardoVal/ludorum-game-reversi.js
https://github.com/LeonardoVal/ludorum-risky.js
https://github.com/LeonardoVal/ludorum-game-mancala.js

https://github.com/SabakiHQ/gtp
A Node.js module for handling GTP engines.

https://github.com/SabakiHQ/Shudan
The Shudan Goban is the Goban component that powers Sabaki (Baduk).

https://github.com/nicolodavis/boardgame.io
https://github.com/turn-based/boardgame.io-angular
State Management for Turn-Based Games 

https://github.com/strawmanbobi/texas-poker-engine
Texas Poker Engine is an open source project which helps you to host a Texas Poker/Holdem game or competition.

https://github.com/pdrum/roomer
Roomer is a framework for writing two-player, turn-based game servers in golang.

https://github.com/Trisfald/weasel
Rust game, Weasel Turn Battle System

https://github.com/JoelOtter/termloop
Terminal-based game engine for Go, built on top of Termbox

# Game Dashboard
https://github.com/szib/no-cambio-tonight
A board games event organiser application.


