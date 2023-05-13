# Valorant

Valorant is an online first-person shooter developed by Riot Games. They created many successful titles like MOBA[^MOBA] game called League of Legends, online card game Legends of Runeterra, mobile game League of Legends: Wild Rift.

[^MOBA]: MOBA is an acronym for multiplayer online battle arena, where two teams fight in real time against each other to win by destroying some sort of the enemy base. <https://www.dictionary.com/browse/moba>

## Regions and Servers

There are currently 6 regions and every region has multiple servers to optimize players' latency[^ping]. For that reason, a player can only play on servers in the player's region.

[^ping]: <https://support-valorant.riotgames.com/hc/en-us/articles/360055678634-Server-Select>

## Main gameplay

Valorant is an online first-person shooter where players form a team of five agents to fight against another squad of five players. One team is called the Attackers and the second one is called the Defenders. The attackers win by eliminating every defender or by planting the spike and defending it to explode. The defenders win by protecting the site from planting the spike or by defusing the spike[^elimination]. This core gameplay is identical to a game called Counter-Strike. The first team that reaches thirteen rounds with two rounds difference wins the game. If the game proceeds to the score 12-12, then the game continues until the first team gets a two-round lead or if any team agrees to draw.

[^elimination]: Note that for Defenders to win, they do not need to kill every Attacker if they did not plant the spike. Which is not true for the Attacker team.

### Agents

The game provides a growing selection of agents divided into four roles: initiators, sentinels, controllers, and duelists. A usual team requires one agent from each category and a fifth agent is determined based on a map or a team preference. That is why the position is called flex.

Agents have five unique abilities including a signature ability and an ultimate ability. Every round agent gets a signature ability free of charge. An ultimate ability is charged by planting or defusing the spike, killing or dying to an enemy, or lastly by grabbing an ultimate orb located on strategic, highly contested places on the map. The number of charges that the ultimate ability requires depends on strength of the ability, it ranges from 6 to 8 charges. The rest of the abilities need to be purchased at the beginning of the round called buying phase. After buying these abilities, they are not lost by dying, only by using them.

#### Controllers

As the name suggests, the controller agent's core responsibility is to control a part of a map using smoke or damaging ability. Smokes cut the map into smaller sections to cut off enemies or to make it easy for allies to gain space by the divide and conquer method.

#### Duelists

Duelists are the most aggressive role. They try to find isolated duels to gain a team person advantage using a disruptive ability. Disruptive ability gains a player an advantage to win a duel if he uses it properly. That can be a flash, stun, or movement ability. Duelists can also use these abilities for gaining space for a team.

#### Sentinels

Sentinels are mostly a defensive role to anchor areas of the map to prevent enemy flanks. They can also be more aggressive and try to flank from the holes of the map that are not protected by the enemy team, or they pressure from the back.

#### Initiators

Initiators support their team while gaining space by clearing out areas of the map, especially corners that are hard to safely check. There are two types of initiator abilities, recon abilities reveal a section of a map, or flash abilities prevent players from having a clear vision to shoot back.

#### Flex

### Maps

Map has a spawn area for the Defenders and the Attackers, two or three plant sites, and usually a mid-lane. To this date, there are 9 different maps. Each one has its special mechanic.

#### Map mechanics

Each map on Valorant website[^map] has a introduction message hinting an unique mechanic, which is unique or introduced for the first time[^first].

| Map       | Unique mechanic               |
| --------- | ----------------------------- |
| Bind      | one-way teleporters           |
| Split     | first vertical zip-line       |
| Haven     | first with 3 sites            |
| Ascent    | breakable horizontally moving doors |
| Icebox    | first horizontal zip-line           |
| Breeze    | trap door[^guess]             |
| Fracture  | split spawn attacker's site   |
| Pearl     | no mechanics                  |
| Lotus     | revolving doors               |

[^map]: <https://playvalorant.com/en-us/maps/>

[^first]: Mechanics marked as *first* are mechanics that used to be unique but not anymore, because they were introduced in newer maps too.

[^guess]: Breeze introduction message is hinting open spaces and long engagement which cannot be the unique mechanic in my opinion. But Breeze does have a trap door which is not present in any of current maps.

### Economy

A player can use credits to buy guns, shields, and abilities.
At the beginning of the first round agents start with 800 credits. After each round players get money based on their performance in the previous round - kills, the team planted/defused the spike, loss bonus, etc.

<https://www.mandatory.gg/en/valorant/guides-valorant/progression-training/how-to-manage-economy-in-valorant/>

### Similarity to CS:GO

Counter-Strike: Global Offensive[^CS:GO] is a FPS title developed by Valve. The core gameplay is very similar: Terrorists and Counter-Terrorists are fighting over two bomb sites. Terrorists try to kill all the Counter-Terrorists or plant and defend a bomb (C4 explosive), while Counter-Terrorists try to protect bomb site from planting the bomb or defusing it.

The biggest difference between Valorant and CS:GO is that CS:GO characters does not have abilities, but they can buy 4 different types of grenades.

[^CS:GO]: <https://counterstrike.fandom.com/wiki/Counter-Strike:_Global_Offensive#Game_Modes>

## Modes

### Fun modes

Except the main gameplay there are special modes that would not be possible in a normal mode.

| Mode      | Mode description               |
| --------- | ----------------------------- |
| Swiftplay   | Same as the main gameplay, but team wins when they reach 5 round wins           |
| Deathmatch  | Free for all mode and when a player dies, he respawns right back |
| Escalation  | Team deathmatch but with 12 random weapons based on team weapon progression |
| Spike Rush  | Every attacker has a spike and everyone has a same gun |
| Replication | Everyone plays as a same agent |

### Custom game

A player can create a custom game, where player can invite other players and freely choose game specification that player desires (map, mode, server, number of players, ...). Custom games are used heavily used for games with friends, custom matchmaking, or scrims[^scrim].

[^scrim]: Scrim is abbreviation for scrimmage. This term is used (nowadays not only) in professional scene, where two teams play practice matches as a preparation for real professional games. The term is also not used only in Valorant or FPS games, but various other game genres where pro players can make a custom game.

### Competitive mode [TODO]

This game mode is equivalent to the main gameplay, but players are evaluated based on their performance. When a player begins his competitive journey, the player plays five opening games after which the player gets a rank and a tier with a 50 rank rating (RR).

#### Acts [TODO]

#### Rank system

Players are divided into ranks based on their matchmaking rating (or MMR[^MMR][^API]). Most of the ranks have three tiers: 1, 2, and 3; the higher the better. Players get a higher tier if they reach 100 RR or they drop down a tier if they lose a game with 0 RR. After reaching tier 3 and 100 RR they rank up, or after losing a game at tier 1 with 0 RR they drop down a rank. Ranking for Immortal and Radiant works differently, the threshold for Immortal and Radiant is different for each region. Also, there can be only 500 players in Radiant in each region.

<table>
  <tr>
    <th>Rank</th>
    <td>Iron</td>
    <td>Bronze</td>
    <td>Silver</td>
    <td>Gold</td>
    <td>Platinum</td>
    <td>Diamond</td>
    <td>Ascendant</td>
    <td>Immortal</td>
    <td>Radiant</td>
  </tr>
  <tr>
    <th>Tiers</th>
    <td>3</td>
    <td>3</td>
    <td>3</td>
    <td>3</td>
    <td>3</td>
    <td>3</td>
    <td>3</td>
    <td>3</td>
    <td>1</td>
  </tr>
</table>

Example of Immortal and Radiant thresholds in EU region[^threshold]:

| Rank | RR |
| ---- | -- |
| Immortal 2 | 100 |
| Immortal 3 | 200 |
| Radiant | 550 |

[^MMR]: Even though Valorant mentions only about MMR and RR, in their Valorant API, they use variable called `elo` instead of `mmr`. Elo rating is a number measuring a strength of a player compared to other players. It is named after Hungarian physics professor Arpad Elo in the United States. The Elo rating system was first used in Chess. <https://www.chess.com/terms/elo-rating-chess>

[^API]: <https://api.henrikdev.xyz/valorant/v1/account/velociraptorv/tuan>

[^threshold]: <https://support-valorant.riotgames.com/hc/en-us/articles/4405964120339>

#### Issues with competitive mode

##### Cheating

###### Vanguard

Riot Vanguard[^Vanguard] is Riot Games' anti-cheat and security software for Valorant. Vanguard is launched with device's startup and cannot be turned off at any time if a player wants to play the game.

[^Vanguard]: <https://support-valorant.riotgames.com/hc/en-us/articles/360046160933-What-is-Vanguard>

###### Stats

In August 2020, Valorant reported[^VN] that 3% of the player base received a cheat report and only 0.6% of the player base received a cheat report by more than one player. Of course, not everyone who receive a cheat report is definitively a cheater, so Valorant provided more stats: 53% of cheaters were banned before they were reported and 60% of players with 20 and more reports were banned after a review.

With no concrete number we cannot say how many cheaters are there. Valorant does not provide stats about number of players, but there is an estimate made by activeplayer.io[^AP]. Based on their statistics, there were approximately 20,760,144 active players in August 2020. Let's say every player that received more than one cheating report is a cheater[^me]. Combined with the number of active players, then there might be 124,560 cheaters. Valorant were very proud in their post, but with very rough number of 100,000 cheaters, it does not sound that impressive to me.

CS:GO does not provide statistics too, but a CS:GO stats website Leetify[^leetify] says, that 268,267 teammates or enemies of players that uses Leetify were banned by VAC[^VAC] between May 2022 and April 2023.

[^leetify]: Leetify does not have permissions to player's stats unless they consent to it. That means that the number of cheaters are relative only to Leetify users, not the overall player base. There were approximately 150,000 Leetify users. <https://www.reddit.com/r/GlobalOffensive/comments/n4v2so/we_are_leetify_ask_us_anything/> <https://leetify.com/bans> => (24870, 22382, 18494, 26185, 23439, 20927, 14355, 18333,20768, 20276, 29028, 29210)

[^VAC]: VAC is acronym for Valve Anti-Cheat and it is a Valve's equivalent for Riot Games' Vanguard.

[^VN]: <https://playvalorant.com/en-us/news/dev/valorant-anti-cheat-cheater-reported/>

[^AP]: <https://activeplayer.io/valorant/>

[^me]: Throughout my time with Valorant, if my enemies did not lie, I'm one of the players that received more than one cheat report, but I promise I haven't cheated.

##### Smurfing

Smurf is an alternate account of a player with a significantly lower MMR than the MMR on player's main account. Players often use smurf to play with friends with lower rank[^VS]. Tarik himself smurfs too when playing with his friends, so their overall team MMR is not too high for his friends to play[^smurf].

[^VS]: <https://playvalorant.com/en-us/news/dev/valorant-systems-health-series-smurf-detection/>

[^smurf]: <https://youtu.be/_secTsStABY?t=18114>

## Pro play

In April 2022 Riot Games announced a new Valorant esport format and with that they claim to be today's fastest growing esport[^FGE]. Riot games host a global tournament called Valorant Champions Tour where pro players compete against each other throughout the year[^VCT].

[^FGE]: <https://valorantesports.com/2023-format-reveal>

[^VCT]: <https://valorantesports.com>

## Streaming

Outside practicing, competing and resting, pro players often stream their Valorant ranked games on streaming platforms, like Twitch. Since pro players have usually a large fan base, they get a lot of attention on their streams. Not only pro players get a lot of views on their stream but also content creators, usually former pro players. But what if someone, who is the streamer playing against, decides to open their stream?

## Issues with streaming Valorant

Riot games have not officially reacted to sniping or crypto-throwing, but in their early patches[^patch], they added option to hide player's name outside player's party and hide names of others outside player's party[^hide].

[^patch]: Patch or patch notes are updates to a game to make a game more fair and enjoyable. <https://valorant.fandom.com/wiki/Patch_Notes>

[^hide]: <https://playvalorant.com/en-gb/news/game-updates/valorant-patch-notes-1-07>

### Queue-sniping

Queue-sniping is when someone joins queue in the same region at the same time as a streamer to get into the same game. Queue-sniping can be easily done by visiting streamer's stream and then join queue exactly when the streamer joins the queue.

#### tarik vs TariksLeftNut

In Episode 5: Act 3, a player called TariksLeftNut played in total 171 games and in 38 he played with tarik[^TLN]. His second most played player with was Stewie2K with 13 games, while TariksLeftNut did not party-queue with any of them. There is a twitch clip[^QS] where tarik is AFK during agent select and his name is hidden from players outside his party. Because tarik hasn't chose his agent yet, his teammate called "I fill", which means he is willing to last pick an agent that the team needs. And that is when TariksLeftNut wrote "tarik has reyna". When tarik came back from being AFK after 15 seconds, he indeed picked agent called Reyna.

It is safe to speculate that TariksLeftNut with high percentage  queue-sniped tarik since he was in his every fifth game, which is not usual, since TariksLeftNut does not have this luck with any other players.

[^TLN]: <https://tracker.gg/valorant/profile/riot/TariksLeftNut%23hairy/matches?season=aca29595-40e4-01f5-3f35-b1b3d304c96e>

[^QS]: <https://clips.twitch.tv/PolishedAmusedShieldAMPEnergyCherry-k4NV3mPbcIX1yoLH>

### Stream-sniping

Stream-sniping is when someone in streamer's enemy team visits streamer's stream to gather information about the game (strategy, players buys and location on the map) that are not visible to the stream-sniper in game, thus gaining unfair advantage.

Many streamers[^complain] have complaint since the beginning of the game, that stream-sniping is annoying. Somehow enemy always know where the streamer is.

[^complain]: <https://twitter.com/flexinja/status/1499090315076157445>

#### Stream-sniping in pro play

Before 1st of February 2022 there was no rule that would forbid coaches to watch live their team play on official Riot stream. Basically coaches could stream-snipe enemy team  and then suggest a counter-strategy during breaks or between games, when coaches are allowed to talk to coach's team. This matter was brought up[^broughtup] by coach of Soniqs that time during Nerd Street Gamers: Winter Championship and was confirmed[^confirm] by NSG Josie - Esports Operations Manager for Nerd Street. Since this was a huge issue, a few hours later, Josie informed about NSG and VCT rule book update that prohibited coaches from watching live broadcast of their teams playing[^update].

[^confirm]: <https://twitter.com/sullycasts/status/1488637656053526537>
[^broughtup]: <https://twitter.com/x0tek/status/1488602393097175040>
[^update]: <https://twitter.com/x0tek/status/1488660037572702214>
  
### Crypto-throwing

- betting sites are not public, since its against valorant rules and thats why we can sometimes only see tweets about it
- RRV clan
- <https://twitter.com/WedidOfficial/status/1561138703417868289>

### Possible solutions

- stream delay
  - not optimal for interaction between streamer and viewers
- minimap cover
  - not effective since the information can still be gathered through streamer's point of view
- hide valorant window when queuing up
  - tedious for the streamer
  - annoying for the viewers + still high chance of getting queue-sniped
  - that prevents queue-snipe but not stream-snipe
- not streaming at all
  - :)
- custom queue
  - Pro City!