# Deckdungeon

Deckdungeon is a cooperative roguelike collectible [card](Card.md) game with a [great style](Style.md).

## Mockups
Mockups are done in [excalidraw.com](https://excalidraw.com/).

## Concepts
- Earning and opening loot boxes as core gameplay mechanic, not selling lootboxes
- Building perfect characters from [drops/loot boxes](Lootboxes.md), inspired by games like Pokemon or Diablo

## Main Systems
- [Dungeon](Dungeons.md) exploration with a party of characters to collect [ressources](Resources.md) and advance the map
- Build a [persistent base](Base.md) from those ressources
- Collect and customize a [party of characters](Characters.md)
- Trade cards and lootboxes on a [market](Market.md)

## Releases
- Combat prototype (CLI)
  - One scenario combat card with predefined characters with only 2x and 0.5x targetted damage cards, enemies auto end activation
  - Enemy AI: Enemies have only "Deal 1x damage to one enemy" cards. Play as many damage cards as possible, target highest aggro, end activation
- Combat prototype (Web)
- Dungeon combat prototype
  - A dungeon deck of multiple scenario combat cards from combat prototype
  - One boss card with single, stronger enemy (same AI)
- Dungeon prototype
  - Dungeon with shuffled deck, boss card in last 30%
  - Add more (non-combat) scenario cards to dungeon deck iteratively

- Alpha 1 (One preconfigured dungeon run from the Alpha set)
- Alpha 2 (User accounts, saving dungeon run stats)
- Alpha 3 (Drops from dungeon run, customize characters from those)

## Sets
[Alpha Set](./SetAlpha.md)