---
title: "Pigpen Cipher"
date: 2022-04-03T17:06:54-06:00
weight: 30
thumbnail: "pigpen.png"
summary: "A particular cipher that uses grids to define a unique symbol for each letter."
---

The [pigpen cipher] is a simple and well-known substitution cipher that
uses lined grids to define unique symbols for each letter in the alphabet.
There are several variants of the pigpen cipher, but a common substitution
table looks like this.

{{< example-image src="/img/puzzles/cipher/pigpen.svg"
                  width="350px" height="112px" >}}

Each letter in the pigpen cipher is defined by the border of its region.
For example, E is in the middle of the grid, surrounded by borders, so it
is represented by a square. B, above it, has an open border on the top, so
it is represented by a box with an open top.

Ultimately, this leaves a code that looks like this.

{{< example >}}
<p>
<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenA.svg" >}}{{< ii "/img/puzzles/cipher/pigpenG.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}{{< ii "/img/puzzles/cipher/pigpenN.svg" >}}{{< ii "/img/puzzles/cipher/pigpenT.svg" >}}</div> &nbsp;&nbsp;&nbsp;{{< ii "/img/puzzles/cipher/pigpenQ.svg" >}},
</p>

<p>
<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenT.svg" >}}{{< ii "/img/puzzles/cipher/pigpenH.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenD.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}{{< ii "/img/puzzles/cipher/pigpenA.svg" >}}{{< ii "/img/puzzles/cipher/pigpenD.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenD.svg" >}}{{< ii "/img/puzzles/cipher/pigpenR.svg" >}}{{< ii "/img/puzzles/cipher/pigpenO.svg" >}}{{< ii "/img/puzzles/cipher/pigpenP.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenF.svg" >}}{{< ii "/img/puzzles/cipher/pigpenO.svg" >}}{{< ii "/img/puzzles/cipher/pigpenR.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenT.svg" >}}{{< ii "/img/puzzles/cipher/pigpenH.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenM.svg" >}}{{< ii "/img/puzzles/cipher/pigpenI.svg" >}}{{< ii "/img/puzzles/cipher/pigpenC.svg" >}}{{< ii "/img/puzzles/cipher/pigpenR.svg" >}}{{< ii "/img/puzzles/cipher/pigpenO.svg" >}}{{< ii "/img/puzzles/cipher/pigpenF.svg" >}}{{< ii "/img/puzzles/cipher/pigpenI.svg" >}}{{< ii "/img/puzzles/cipher/pigpenL.svg" >}}{{< ii "/img/puzzles/cipher/pigpenM.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenI.svg" >}}{{< ii "/img/puzzles/cipher/pigpenS.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenB.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}{{< ii "/img/puzzles/cipher/pigpenH.svg" >}}{{< ii "/img/puzzles/cipher/pigpenI.svg" >}}{{< ii "/img/puzzles/cipher/pigpenN.svg" >}}{{< ii "/img/puzzles/cipher/pigpenD.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenT.svg" >}}{{< ii "/img/puzzles/cipher/pigpenH.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenG.svg" >}}{{< ii "/img/puzzles/cipher/pigpenR.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}{{< ii "/img/puzzles/cipher/pigpenE.svg" >}}{{< ii "/img/puzzles/cipher/pigpenN.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "/img/puzzles/cipher/pigpenC.svg" >}}{{< ii "/img/puzzles/cipher/pigpenU.svg" >}}{{< ii "/img/puzzles/cipher/pigpenR.svg" >}}{{< ii "/img/puzzles/cipher/pigpenT.svg" >}}{{< ii "/img/puzzles/cipher/pigpenA.svg" >}}{{< ii "/img/puzzles/cipher/pigpenI.svg" >}}{{< ii "/img/puzzles/cipher/pigpenN.svg" >}}</div>.
</p>
{{< /example >}}

Using the pigpen cipher above, the shapes can be matched to letters that
spell out this secret message.

{{% example %}}
AGENT Q,

THE DEAD DROP FOR THE MICROFILM IS BEHIND THE GREEN CURTAIN.
{{% /example %}}

Because the pigpen cipher is quite well-known, there is a good chance that
players will already be familiar with it and will be able to decode a
message without a provided substitution table. Thus, consider providing the
decoding table before providing the message.


[pigpen cipher]: https://en.wikipedia.org/wiki/Pigpen_cipher
