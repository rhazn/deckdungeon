# Combat
Combat is needed to resolve combat scenario cards.

## Enemies
Combat is fought against one or multiple [characters](./Characters.md) that are spawned on a [scenario card](./Card.md) and displayed on top of the screen.

## Player characters
The three player characters are displayed at the bottom of the screen in a triangle formation. The character with the current/last played turn is shown on top and enlarged, the other two greyed out.

## Combat start
Player characters do not change their statistics between combats.

On combat start every character gains:
- an aggro value of 0

## Turns
Characters take activations according to their initiative (from high to low). Once every character has had an activation a turn ends.

On activation start the character draws a hand of 5 cards from their skill deck and restores their action points. If the character is a player character they move to the top of the triangle and their hand is displayed above them.

During their activation a character can:
    - play skill cards from their hand if they can pay the action costs
    - end their activation

## Targeting
If a card can target a single enemy players can drag it over the enemy to target.

Enemies base their targeting on the aggro value of player characters, typically preferring high aggro characters.

## Damage and Knocked out
Some cards deal damage. Damage is reduced by the armor value of the character (to a minimum of 1) and then removed from the characters hitpoints. Once a character is reduced to zero or less hitpoints they are knocked out. Knocked out characters automatically skip their activation.

## Combat end
Combat ends when all enemies or player characters are knocked out. If all player characters are knocked out the dungeon is lost, otherwise the scenario is passed.