# Fully Loaded
Subordinate traders prefer fully-loaded trade runs.

- Our GitHub repo: https://github.com/Vectorial1024/v1024_fully_loaded
- Our EgoSoft Forums link: https://forum.egosoft.com/viewtopic.php?t=464437
- Our Steam link: https://steamcommunity.com/sharedfiles/filedetails/?id=3299678598
- Our Nexus link: https://www.nexusmods.com/x4foundations/mods/1462

> Efficient logistics: that's how simple it is!

## Deprecation Notice
It turns out, station trading logic is much more problematic than the shallow observation of "does not use all of the cargo space".
[Logistics Optimization](https://github.com/Vectorial1024/v1024_logistics_optimization) has been set up to better manage the relevant fixes to the station trading logic. Users are advised to remove this mod and use Logistics Optimization instead.

## Quick Start Guide
TL/DR: No user action required!

Vanilla AutoTrade looks at the amount traded, which makes sense: more goods means more profits. However, as we all know, this sometimes results in M/L traders running around with only 100 energy cells just because the profit margin is very nice.

This mod tells traders to look at their cargo limit when thinking about which trade action (i.e. buy/sell) is best. Technically speaking, trade runs that does not use the full cargo limit are penalized.

This mod can work together with my other trading mods, e.g. Station Logistics.

### Notes
For performance reasons, in the vanilla AutoTrade script, the buying step and the selling step are separate. It is therefore possible subordinates exporting wares may decide to load up everything, but only manage to sell some of the loaded wares (e.g. drug station exporting drugs). This is vanilla behavior, is not part of this mod, and is not changed.
