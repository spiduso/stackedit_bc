# Pro City Bot

## What should we learn from other alternatives

- Apex's The Realm
  - thorough application review system outside (former) pro players for maintaining high skill ceiling but approving new up and coming players. (rank only requirement might not be enough)
  - API for Twitch bot for better viewing experience
  
- League of Legends' Champions Queue
  - automated Twitter bot when game starts with players' Twitch <https://twitter.com/ChampQueueWard>
  - more fair Elo system, where player with the most games and an average win rate ratio will not be ahead of player with decent amount of games and incredible win rate ratio.
  - better matchmaking system where the competing teams are as balanced as possible while maintaining desired roles of players

- CS:GO's ESEA and FACEIT

- Pro City's NeatQueue
  - short matchmaking process
    - automated team division
    - automated map selection
    - map preference
    - role preference
  - friendly button only UI
  
## New features that are not in NeatQueue

- new status `Down to play` which does not oblige player to matchmaking unlike joining queue

## Possible features

- Valorant bot that creates a lobby, invites players, sets the chosen map, best server based on players ping and sets correct settings => prohibited[^PN]
[^PN]: <https://www.riotgames.com/en/privacy-notice>

## Unresolved issues

- elo system cannot be based on game performance since VALORANT forbid using Valorant API for third party matchmaking[^valoAPI]. Even sites like tracker.gg where I get most of data from Valorant does not support getting data from Valorant API while data from Apex, CS:GO and other titles are free to grab from tracker's API[^trackerAPI].
  - maybe screenshot after the game ?

[^valoAPI]: <https://www.riotgames.com/en/DevRel/valorant-api-launch>

[^trackerAPI]: <https://tracker.gg/developers/docs/getting-started>