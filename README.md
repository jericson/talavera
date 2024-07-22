# Talavera

Source for Talavera, an 18-card game inspired by Azul.

![Talavera tile steps](./steps.jpg)

## Components

Print [the cards](cards.pdf) double-sided (long edge) on card stock or
single-sided to put in card sleeves. Be sure the colors of the squares
match front and back.

Two cards have a rules summary on one side and a **player's card** with
the four rectangles on the other side. 

The remaining 16 cards have four squares (**tiles**) arranged in a
square on one side. This is the **market** side. The other side has
the same tiles grouped by color and spread to the edge of the
card. This is the **placement** side.

## Two player rules

Talavera consists of 4 rounds of two phases. Give each player a
player's card. Randomly decide on a first player for the first
round. Each round, swap who drafts first so that each player has
drafts first two times.

### Draft phase

Randomly deal four cards in the center of the table with the market
side up.

> **Note**: The deck should be put away so that neither player can see
> the tiles on the top card. This might be accomplished by placing a
> playing card on the deck and dealing from the bottom, putting the
> deck in a bag or using a wallet game case to hide the deck.

Players take turns drafting one card until the market is empty. Each
player will have two cards to place.

### Placement phase

Each player flips their drafted cards to the placement side and tucks
them under one of the empty colors on their player's card. Be sure
that all tiles of the matching color are visible.

> **Note**: It should be possible to arrange the two cards so that
> other colors are not visible. This is optional as long as all the
> tiles of the placed color can be seen by both players.

### Winning

Players are only eligible to win if they have placed a full set of tiles:

* One color with _at least_ 4 tiles.
* Another color with _at least_ 3 tiles.
* A third color with _at least_ 2 tiles.
* The final color with _at least_ 1 tile.

The tie breaker is fewest excess tiles.

> **Example**: Player A has 5 red tiles, 4 light blue tiles, 2 yellow
> tiles, and 1 dark blue tile. That's a full set of tiles, so Player A
> is eligible for the win. There are 2 excess tiles whether red or
> light blue fills the 4 tile requirement.
>
> Player B has 4 dark blue tiles, 3 yellow tiles, and 2 light blue
> tiles. If they place 1 or 2 red tiles, Player B would win because
> they have fewer than 2 excess tiles. If they place 0 red tiles, they
> lose automatically.

## Solo rules

As in the two-player game, solo Talavera consists of 4 rounds of two phases.

### Draft phase (solo)

Shuffle the deck and place the solo rules on top to cover the top
card. Deal two cards from the bottom of the deck with their market
side face up. Select one card and discard the other. Repeat the
process with two more cards so that you have a two tile cards to place.

### Placement phase (solo)

As in the two-player game, tuck your two cards under a free color on
your player's card. Be sure to have all the tiles of the matching
color visible.

### Winning (solo)

The only way to win is by placing a full set of tiles:

* One color with _exactly_ 4 tiles.
* Another color with _exactly_ 3 tiles.
* A third color with _exactly_ 2 tiles.
* The final color with _exactly_ 1 tile.

If you place _any_ excess tiles, you have lost the game.


## Design notes

I designed this game for the second [Decision Space
Jam](https://www.decisionspacepodcast.com/decisionspacejam)---18
Cards. Talavera was inspired by [my all-time favorite
game](https://jlericson.com/2023/10/02/top10.html),
[Azul](https://jlericson.com/2020/01/04/azul-review.html). I've tried
to maintain the design principles that I like best from Michael
Kiesling's classic:

1. **Open information**: All players see the same things on the table.
2. **Interactive draft**: Each time a player selects tiles, it alters
   the state of the draft for other players. Players can manipulate
   the market to ensure their own plans succeed or to thwart the plans
   of other players.
3. **Placement puzzle**: Deciding where to place tiles changes the
   relative value of tiles in future drafts. A partially completed
   color represents a risk that the color might not be available when
   your next turn to draft comes.
4. **Efficiency rewarded**: Nothing feels better than filling a color
   exactly. Nothing feels worse than being forced to take excess tiles
   that drop to the floor.
   
The current design falls a bit short on the interactive draft. Without
being able to change the composition of the markets, I'm left with a
fairly straightforward draft in which the first player has a
meaningful advantage. The final round doesn't feel fair since whoever
is first to draft can hate-draft to victory if the tiles come out
right.

There's also a potential tile-counting problem if one player is
watching what's come so far and anticipates the final draft. One
potential fix to this is to deal the next round of market cards before
the players place the cards they'd just drafted. Alternatively, allow
the player who had just drafted second to see the next market before
locking in their placement. Please let me know if you try one or both
of these variations!

The solo game is literally counting cards. In the final round you know
_exactly_ what you need to draft. If you also know which two cards are
left in the final draft, you can determine if a win is possible in the
penultimate draft.

I'm not sure this is a fatal flaw, however. There is [a fan-made solo
mode for
Azul](https://boardgamegeek.com/filepage/164052/soloplay-azul-v1pdf),
but Azul shines when another player's decisions impact yours. A puzzly
solo mode that takes 5-10 minutes from setup to completion seems like
a decent accomplishment.

Speaking of which, I was pleasantly surprised that I was able to make
my card representation of tiles enjoyable to arrange on the table. I
took inspiration from the splaying mechanism of Innovation to design
the placement side of the tile cards. It weirdly elevate the game to
have the two sides of the cards.

I'm not entirely happy with the simple color squares. I used [Talavera
tiles](https://www.lafuente.com/Mexican-Decor/Talavera-Pottery/Talavera-Tile/)
to decorate our front steps. (See the image at the top of this page.)
At some point I might replace the solid squares with authentic tile
designs. This would have the added advantage of avoiding problems for
colorblind players.

<!-- LocalWords: Talavera Azul puzzly --> 
