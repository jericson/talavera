# Talavera

Talavera is an 18-card game inspired by Azul.

Players compete to decorate a flight of stairs according to customer
specifications.

![Talavera tile steps](./steps.jpg)

## Components

Print [the cards](cards.pdf) double-sided on card stock or
single-sided to put in card sleeves.

One side represents an **order card**. Each of the four colors has a
number, which represents the customer's order for that type of tile.

The others side of the cards have four squares (**tiles**) grouped by
color. Players will take turns drafting these cards in order to
fulfill their customer's order.

## Two player rules

Talavera consists of 4 rounds of two phases. Shuffle the cards and
give each player an order card. Randomly decide on a first player for
the first round. Each round, swap who drafts first so that each player
has drafts first twice.

### Draft phase

Deal four cards in the center of the table with the order side up. The
first player flips two cards and selects one to keep. The second
player flips the other two cards and selects one of the three cards
remaining in the market.

Players take turns drafting one card until the market is empty. Each
player will have two cards to place.

### Placement phase

When each player has two cards, they must pick which color to
keep. Place the cards one corner of the order card to show they've
filled that order.

> **Note**: Only the tiles of that color count toward your score. 


### Winning

In order to fill an order, there must be _at least_ as many tiles of
that color as indicated by the number on the order. Score each order
separately and add up the total score.

* Each fulfilled order is 3 points.
* Subtract 1 point for each excess tile. Orders can't go below 0.
* If there are fewer of a color than required, the order is worth 0 points.

> **Example: The first order is for 3 yellow tiles. The player placed
> 4 yellow tiles, so they completed the order with one excess
> tile. That order is worth 2 points (3 - 1). 
>
> The next order is for 2 red tiles, but the player didn't place any
> red tiles on the order. That's worth 0 points because the order
> wasn't fulfilled.
>
> The third order was for 4 sky blue tiles and the player had exactly
> that. It's worth 3 points for fulfilling the order exactly.
> 
> Finally the 1 azure (dark blue) tile was ordered. The player placed
> 5 tiles of that color and scored 3 points for filling the order and
> lost 4 points for excess tiles. Since the score for an order can
> never go below zero, it scores 0 points.

Add the total score for all four orders and highest score wins.

In case of a tie, congratulate each other on a job well done!


## Solo rules

As in the two-player game, solo Talavera consists of 4 rounds of two phases.

### Draft phase (solo)

Shuffle the deck and place the solo rules on top to cover the top
card. Deal two cards from the bottom of the deck with their tile
side face up. Select one card and discard the other. Repeat the
process with two more cards so that you have a two tile cards to place.

### Placement phase (solo)

As in the two-player game, rotate your two cards so that all the tiles
of the chosen color are visible.

### Winning (solo)

The only way to win is by fulfilling the customer's order _exactly_.

If you place _any_ excess tiles, you have lost the game.


## Design notes

I designed this game for the second [Decision Space
Jam](https://www.decisionspacepodcast.com/decisionspacejam) — 18
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
   
Dan R, on the Decision Space Discord server, helped me solve some of
the problems I originally had with the draft. He suggested putting
tiles on all 18 cards to avoid card counting. He also came up with the
idea for giving the first player to draft a choice of two cards
instead of all four.

I'm considering an explicit cooperative mode. One of the things I like
about Azul is that people naturally play in the interest of their own
goals without worrying too much about other players. Cutthroat play
comes with experience. 

Based on player feedback, I added a simple scoring system to encourage
a more relaxed way to play. It's still a zero sum game, but scoring
makes it possible to lose by a small amount. Often a close game feels
better for the loser than a binary win or lose end state.


Drafting games resist a satisfying solo mode. There is [a fan-made solo
mode for
Azul](https://boardgamegeek.com/filepage/164052/soloplay-azul-v1pdf),
but Azul shines when another player's decisions impact yours. A puzzly
solo mode that takes 5 minutes from setup to completion seems like
a decent accomplishment.

Speaking of which, I was pleasantly surprised that I was able to make
my card representation of tiles enjoyable to arrange on the table. I
took inspiration from the splaying mechanism of Innovation to design
the tile cards. An early version of the game required splaying tiles,
but the current version allows players to fiddle with their cards as
much or as little as they like.

I'm not entirely happy with the simple color squares. I used [Talavera
tiles](https://www.lafuente.com/Mexican-Decor/Talavera-Pottery/Talavera-Tile/)
to decorate our front steps. (See the image at the top of this page.)
At some point I might replace the solid squares with authentic tile
designs. This would have the added advantage of avoiding problems for
colorblind players.

<!-- LocalWords: Talavera Azul puzzly --> 
