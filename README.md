# ServerPatches
A global patch for multiple ways to crash servers including exploits and other methods. Adding more features soon!

## Features:
- Fixes the lectern exploit (caused by sending inventory click packets while using a lectern) - [EXAMPLE](https://www.youtube.com/watch?v=SvdO8ZSHQdo)
- Fixes out of bounds inventory click packets (wow so many issues with this packet!) - [EXAMPLE](https://www.youtube.com/watch?v=MIJR-nuwFi4)
- Simple packet limiter built in (Not currently reccomended for use on velocity!)

## Requirements: 
- Velocity: [Protocolize](https://github.com/Exceptionflug/protocolize/)
- Spigot: [ProtocolLib](https://github.com/dmulloy2/ProtocolLib/)
  
## Credits:
- Pyr#6969 - Initial patch for the inventory click exploit and heavily based on their code

## Notes:
- If you know of any other exploits please open a [new issue](https://github.com/summiner/ServerPatches/issues/new) and give detail about the exploit

## In Development:
- None (open ticket for more features!)
