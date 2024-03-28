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

{{< example-image src="pigpen.svg"
                  width="350px" height="112px" >}}

Each letter in the pigpen cipher is defined by the border of its region.
For example, E is in the middle of the grid, surrounded by borders, so it
is represented by a square. B, above it, has an open border on the top, so
it is represented by a box with an open top.

Ultimately, this leaves a code that looks like this.

{{< example >}}
<p>
<div style="display: inline; white-space: nowrap;">{{< ii "pigpenA.svg" >}}{{< ii "pigpenG.svg" >}}{{< ii "pigpenE.svg" >}}{{< ii "pigpenN.svg" >}}{{< ii "pigpenT.svg" >}}</div> &nbsp;&nbsp;&nbsp;{{< ii "pigpenQ.svg" >}},
</p>

<p>
<div style="display: inline; white-space: nowrap;">{{< ii "pigpenT.svg" >}}{{< ii "pigpenH.svg" >}}{{< ii "pigpenE.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenD.svg" >}}{{< ii "pigpenE.svg" >}}{{< ii "pigpenA.svg" >}}{{< ii "pigpenD.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenD.svg" >}}{{< ii "pigpenR.svg" >}}{{< ii "pigpenO.svg" >}}{{< ii "pigpenP.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenF.svg" >}}{{< ii "pigpenO.svg" >}}{{< ii "pigpenR.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenT.svg" >}}{{< ii "pigpenH.svg" >}}{{< ii "pigpenE.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenM.svg" >}}{{< ii "pigpenI.svg" >}}{{< ii "pigpenC.svg" >}}{{< ii "pigpenR.svg" >}}{{< ii "pigpenO.svg" >}}{{< ii "pigpenF.svg" >}}{{< ii "pigpenI.svg" >}}{{< ii "pigpenL.svg" >}}{{< ii "pigpenM.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenI.svg" >}}{{< ii "pigpenS.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenB.svg" >}}{{< ii "pigpenE.svg" >}}{{< ii "pigpenH.svg" >}}{{< ii "pigpenI.svg" >}}{{< ii "pigpenN.svg" >}}{{< ii "pigpenD.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenT.svg" >}}{{< ii "pigpenH.svg" >}}{{< ii "pigpenE.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenG.svg" >}}{{< ii "pigpenR.svg" >}}{{< ii "pigpenE.svg" >}}{{< ii "pigpenE.svg" >}}{{< ii "pigpenN.svg" >}}</div> &nbsp;&nbsp;&nbsp;<div style="display: inline; white-space: nowrap;">{{< ii "pigpenC.svg" >}}{{< ii "pigpenU.svg" >}}{{< ii "pigpenR.svg" >}}{{< ii "pigpenT.svg" >}}{{< ii "pigpenA.svg" >}}{{< ii "pigpenI.svg" >}}{{< ii "pigpenN.svg" >}}</div>.
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
