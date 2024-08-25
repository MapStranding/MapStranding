# Death Stranding interactive map

This tool is a route planning tool for the game "DeathStranding". Please be aware that it is a personal project and still work in progress.
I appreciate any feedback and suggestions, but please keep in mind that as a hobbyist I can't utilize unlimited time for this project and need 
to decide which features are in scope of this project and which are not. I've built it for myself in the first place and this repository is more 
about sharing the state that I have anyways than about initiating a continuously maintained project.

Compared to other maps available online it's less about collecting as much locational data as possible but more about handling connections between places and supplying basic route planning capabilities. This includes calculation of needed stack sizes and amounts as well as finding the most efficient traversal for the network of connections by given stocks and resource demands and their locations.

## Features:
- Representation of static storage and building sites (preppers & settlements, road pavers) as well as dynamic locations (shelters and buildings with resource demands)
- Computation of most efficient material stack combination
- Computation of most efficient route between storage and demand locations
- Configurable and extendable network. You can add new waypoints and connections according to your worlds state and pathes you have cleared and also remove predefined connections.

## Limitations:
- Custom structures like shelters are not fully implemented yet. You can add demand nodes, but no structures with own inventory that hold resources, like shelters.
- No responsive UI yet. To handle node locations i've tied them statically to the coordinates on the background picture. That was an easy first throw to get it somehow running, but I've already recognized it has the downside that I've needed to uncouple the UI from the page zoom. So UI might appear either to small or big for you, depending on the browser window size. I need to restructure most things to address this, so it might take a while until this is adressed.
- Player inventory capacities do not include the slots on the suit directly.

## Thanks to:
[u/KanikaD](https://www.reddit.com/user/KanikaD/) for the [awesome map](https://reddit.com/r/DeathStranding/comments/1athe8v) I've built upon.  
[u/OriginalDarkSolaire](https://www.reddit.com/user/OriginalDarkSolaire) for [this very informational post](https://www.reddit.com/r/DeathStranding/comments/ifl5mg/) about vehicle capacities.
