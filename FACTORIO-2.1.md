# Factorio 2.1 validation

Version 1.0.1 was checked on Factorio 2.1.24 with Space Age and Any Planet Start enabled.

- Research requires automation, logistic, chemical, space and electromagnetic science packs. Neither Vulcanus discovery nor metallurgic science appears in its prerequisite chain. Research remains 500 units at 20 seconds each.
- Crafting remains 4 steel plates, 8 low-density structures and 10 refined concrete per foundation, with a 20-second recipe.
- Placement retains both Fulgora shallow oil-ocean variants and the original supported water/wetland tiles. Item, recipe, technology and tile names are preserved.
- Fresh loading and loading a save from Early Foundations 0.1.5 passed with the current mod selection. Repeated 1,200-tick consistency runs passed after switching to this fork.
- Item, tile and technology icon paths resolve to the fork package, with image dimensions matching their declared sizes. Terrain graphics and placement/balance properties remain unchanged.
- A compatibility profile with layered vanilla foundation icons verifies that the fork retains its own item/tile artwork. Short-pile foundations sort before advanced foundations.
