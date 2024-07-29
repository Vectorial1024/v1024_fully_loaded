# Fully Loaded
(WIP) Subordinate traders prefer fully-loaded trade runs.

(links etc)

> Efficient logistics: that's how simple it is!

## Quick Start Guide
TL/DR: No user action required!

Vanilla AutoTrade looks at the amount traded, which makes sense: more goods means more profits. However, as we all know, this sometimes results in M/L traders running around with only 100 energy cells just because the profit margin is very nice.

This mod tells traders to look at their cargo limit when thinking about which trade action (i.e. buy/sell) is best. Technically speaking, trade runs that does not use the full cargo limit are penalized.

This mod can work together with my other trading mods, e.g. Station Logistics.

### Notes
For performance reasons, in the vanilla AutoTrade script, the buying step and the selling step are separate. It is therefore possible subordinates exporting wares may decide to load up everything, but only manage to sell some of the loaded wares (e.g. drug station exporting drugs). This is vanilla behavior, is not part of this mod, and is not changed.
