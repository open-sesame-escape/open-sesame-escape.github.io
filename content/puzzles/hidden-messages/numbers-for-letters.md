---
title: "Numbers for Letters"
weight: 30
thumbnail: "numbers-for-letters.png"
summary: "Hide a number code by replacing letters in a message with similar
looking numbers."
---

A numeric code is easy to hide in a message by replacing some of the
letters in the message with numbers. Several letters look similar to one of
the numeric digits, so they can be subtly replaced.

{{% example caps=on %}}

Captain's Log

The starship Faustus r3ached the outskirts of Alpha Centauri only to make a
trou8ling discovery. We have encountered life fØrms free floating in space
r4ther than bound to a planet. The organi5m we dubbed "death worm" has
already terminated over a quarter of the crew.

{{% /example %}}

In the above message there are 5 numbers, which list out the code 38045.

Hiding a code like this is easy, especially when using all caps in the
message. The following table, adapted from [leet], provides some suggested
substitutions.

| Number | Letters it can replace |
| ------ | ---------------------- |
| Ø      | O, Q |
| 1      | I, L |
| 2      | Z |
| 3      | E |
| 4      | A |
| 5      | S |
| 6      | G |
| 7      | J, T |
| 8      | B, X |

When substituting a number digit for a letter, it is important to be able
to distinguish the two. Otherwise, it will be impossible for the players to
solve the puzzle. You may need to add distinguishing features. For example,
a zero is indistinguishable from an "O", so you will need to add a slash to
the zero (i.e. Ø).

This puzzle tends to be easy to solve. A variation to make this more
challenging for experienced players is to spell out one of the digits
instead of using this substitution. Here is a message I once used.

{{% example caps=on %}}

The fire has been called Øff, my friend. No one is coming to h3lp you. You
might as well come out and join the others. I promise I won’t hur7 you.

{{% /example %}}

The players quickly found the code 037. But that did not fit any of the
locks. The difficult part of the puzzle is to recognize that the word "one"
is part of the message. Inserting a "one" into the digits, you get the
proper code 0137.


[leet]: https://simple.wikipedia.org/wiki/Leet
