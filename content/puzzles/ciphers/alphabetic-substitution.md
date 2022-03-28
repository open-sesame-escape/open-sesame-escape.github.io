---
title: "Alphabetic Substitution"
date: 2022-03-27T16:53:25-06:00
weight: 10
thumbnail: "alphabetic-substitution.png"
summary: "Make a table converting each letter to another letter. Reverse the process to get the message back."
---

A very simple way to make a cipher is to create a table that substitutes
each letter with another letter. The table is simple. Make two rows of
letters: the first row with the letters in order and the second row with
the letters in a different order.

One common way of creating such a table is to simply rotate the letters for
the second row. (This specific type of alphabetic substitution is known as
[Caesar cipher].) Here is an example of rotating by 5 letters.

{{% example %}}
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|
{{% /example %}}

When creating the encrypted text, look up each letter in the bottom row and
replace it with the letter in the top row. You end up with text like this:

{{% example %}}
YMJ UFXXBTWI NX GJQQDGZYYTS
{{% /example %}}

Now, when players find this message and the cipher table, they can do the
reverse lookup and reveal the clear text.

{{% example %}}
THE PASSWORD IS BELLYBUTTON
{{% /example %}}

You can choose any character mapping you like. For simplicity, you might
try the [ROT13] system, which has the letters rotated 13 places.

{{% example %}}
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|
{{% /example %}}

The convenience of the [ROT13] cipher is that the table works both ways.
Letter "A" transforms to "N" and letter "N" transforms back to "A".
Likewise, "B" transforms to "O" and vice versa, and so on. This property
makes it less likely to make a mistake when encoding or decoding.

Another cipher with the same property can be formed by reversing the order
of the letters.

{{% example %}}
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Z|Y|X|W|V|U|T|S|R|Q|P|O|N|M|L|K|J|I|H|G|F|E|D|C|B|A|
{{% /example %}}

You can, of course, randomize the letters in any order that you wish. But
unless you think the players will guess the common cipher, that is likely
more trouble than it is worth.

One final note. Simple alphabetic substitution ciphers are known to be
breakable without the cipher table. In fact, newspapers often feature
"Cryptogram" puzzles that challenge readers to decode a quote encoded with
a random alphabetic substitution cipher. However, that should not be a
problem as it will likely be easier and more fun for players to solve by
finding the decoding table and using that. (If you are really worried about
it, make sure players find the decoding table first.)

On the other hand, you could force players to break the substitution cipher
without a table. But, frankly, this does not make for a good escape room
puzzle. Solving a cryptogram is time consuming and very difficult if you do
not have much experience with them. If you are into cryptograms, it is a
lot easier to get your fix with a puzzle book than to design a whole escape
room.


[Caesar cipher]: https://en.wikipedia.org/wiki/Caesar_cipher
[ROT13]: https://en.wikipedia.org/wiki/ROT13
