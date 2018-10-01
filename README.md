# LibratusEndgames

These files contain data related to endgames generated and solved by the Libratus poker AI. The format is as follow:

-round: The betting round the endgame begins on. Either 3 (for the turn) or 4 (for the river).

-board: The board cards revealed so far, in order. Each card is represented by a two-character sequence using standard poker notation.

-pot: The total amount of money in the pot (each player contributed half of this total)

-reach: The probability, according to the Libratus blueprint strategy, of each player reaching this endgame with each hand. There are a total of 2,652 probabilities in this list. The first 1,326 are for the "out of position" player (the first player to act on the round), while the remaining 1,326 are for the "button" player. Each of the 1,326 probabilities corresponds to a poker hand, ordered as follows: 2s2h, 2s2d, 2s2c, 2s3s, 2s3h, ..., 2sAc, 2h2d, 2h2c, ..., AdAc.
