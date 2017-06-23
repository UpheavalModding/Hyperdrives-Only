# Hyperdrives-Only
Current Version: 1.1.1 (May 10th, 2017).
Built for Stellaris Version 1.6.x.
Workshop Link: http://steamcommunity.com/sharedfiles/filedetails/?id=881020327

# Description
This is a small mod intended to help make late-game Hyperdrive-only matches retain the feel. This modifies Warp, Wormhole, Jump, and Psi Jump Drives into all being Hyperdrive-based FTL, but gives them all different characteristics.

Note: Since this modification modifies all FTL types, selecting Hyperdrive only when creating a game is not necessary. This will only affect what version of hyperdrive is used.



Balance
- Warp: Very long wind-down time, no wind-up time, slow intersteller speeds.
- Hyperdrive: No wind-down time, very long wind-up time, slow intersteller speeds.
- Wormhole: Very long wind-down time, mediumwind-up time, instant travel.
- (Psi) Jump: No wind-down time, short wind-up time, very fast intersteller speeds.



Save-Game Compatibility
This mod should be fully compatible with any save game, but if you are using a FTL tech other than Hyperdrives, you will need to research Hyperlane Mapping before being able to view hyperlanes.



Mod Compatibility
This mod should be fully compatible with everything, but it will not affect any other FTL drives that are added by other mods.



Notes
The defines has been changed to make Hyperdrive FTL types have "1" as the base numbers to use for drive attributes. The drives then modify this to the correct attributes, but this causes drives to currently nearly always display red text even whith upgraded drives. This is intended as at this time as it allows quicker balance changes if needed. 

This can also be handy as it allows one to see at a glance how long it will take to wind-up, wind-down, etc.
Example:
- Warp 2:
+++ Wind-up displays as 11000%. This means it will take 11 days to wind-up.
+++ Wind-down displays as -100%. This means it does not have to wind-down.
- Hyperdrive 1: 
+++ Wind-down displays as 15000%. This means it will take 15 days to wind-down.
+++ Wind-up displays as -100%. This means it does not have to wind-up.



Changelog
- May 10th, 2017: Initial update for 1.6.x (updated supporting version number).
- April 13th, 2017: Rebalanced wormhole drives, added new wormhole drives, and removed the 1 day delay that Hyperdrive and Warp drives experienced.
- April 11th, 2017: Updated localisation file structure. Removed the FLEETORDER_MOVE_SINGLESHIP_WINDOWN_HYPERLANE_EXT text being displayed on drive wind-down.
- April 9th, 2017: Added 1.5.1+ compatibility. Made Hyperlane Mapping a starting tech rather than being event driven.
- March 11th, 2017: Added event to give Hyperlane Mapping at game start.
- March 11th, 2017: Version 1.0.
- March 10th, 2017: Private test upload.
