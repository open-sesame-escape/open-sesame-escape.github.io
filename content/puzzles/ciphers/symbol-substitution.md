---
title: "Symbol Substitution"
date: 2022-03-28T22:08:53-06:00
weight: 20
thumbnail: "symbol-substitution.png"
summary: "Decode a sequence of symbols by replacing each one with a number or letter."
---

The [alphabetic substitution cipher] replaces one letter for another
letter. But who says that the encrypted message has to use the same letters
or numbers as the plain text message? You can use completely different
symbols for the encoded message: hieroglyphics, Braille, emojis,
constellations, or anything else you can think of.

A symbol substitution works the as alphatbetic subtitution, just with
symbols. Here is a simple cipher example using symbols based on zodiac
signs.

{{% example %}}
|♒|♈|♋|♑|♊|♌|♎|♓|♐|♏|♉|♍|
|-|-|-|-|-|-|-|-|-|-|-|-|
|A|D|E|G|H|N|O|R|S|T|U|W|
{{% /example %}}

A message is a sequence of these symbols. It may contain punctuation (as
long as it will not be mistaken for symbols).

{{% example %}}
♑♎ ♌♎♓♏♊ ♒♌♈ ♏♊♋♌ ♍♋♐♏&#8239;. ♏♊♋♌ ♑♎
♐♎♉♏♊&#8239;, ♐♎♉♏♊♍♋♐♏&#8239;, ♒♌♈ ♋♒♐♏&#8239;.
{{% /example %}}

And the decoding happens by finding each symbol in the table and replacing
it with the associated letter.

{{% example %}}
GO NORTH AND THEN WEST. THEN GO SOUTH, SOUTHWEST, AND EAST.
{{% /example %}}

One of the nice things about using a symbol substitution cipher is that the
symbols can be unique and be used across multiple puzzles. Rather than give
the table directly, a seprate puzzle, like [symbol algebra]. And rather than
give a message of symbols outright, the symbols and order can be extracted
from another puzzle, like the grid lookup.


[alphabetic substitution cipher]: ../alphabetic-substitution/
[symbol algebra]: /puzzles/paper-and-pencil/symbol-algebra
