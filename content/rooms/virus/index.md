---
title: "Virus"
date: 2022-07-01T20:39:27-06:00
weight:
thumbnail: "virus.png"
summary: "A new virus outbreak is becoming the next pandemic. Your team must work quickly to avert a world-wide disaster."
---

## Scenario

The players are researchers at a microbiology and infectious diseases
laboratory. The lead researcher of the lab, Dr. Sarah Beaker, has been away
in the field researching a recent outbreak of NEONORO, a deadly and highly
infectious virus, while you work at the home base to understand the nature
of the disease.

Today at work, the players are presented with a package sent from Dr.
Beaker. It [contains a note] (among other clues) in which she is requesting
help from the players.

{{% example %}}
As you know, I have been traveling the world researching NEONORO and
helping where I can. Thank you for taking care of the laboratory in my
absence, but things have gone sideways and now I need your direct help.

First, we need to reestablish communication. General Halftrack, who
originally sponsored this excursion, has suddenly tried to block my
investigations. He has severed my connection to our mail server. We do not
have time to mail letters back and forth.

I cannot fix my connection from here. You must do it from the lab complex.
I am sending you the digital codes to do it.
{{% /example %}}

Dr. Beaker is stranded without communication. The players need to
reestablish this communication.

[contains a note]: initial-mail.pdf


## Office Space (Room 1)

The players start in a room themed as standard office space. Simple office
materials (desk, table, chairs, bookshelf) set the theme.

The players start with a packed of material sent from Dr. Beaker. Other
clue puzzles, particiluar those that are paper based or require a flat
surface, may also be placed around the room.


## Reestablishing Email (Box 1)

Using clues from the package provided by Dr. Beaker's package, the players
reestablish communication by connecting to her secret email.

**Suggested puzzle:** The package contains a piece of paper containing a
[QR fold-in]. When scanned, the solved QR code sends a player's phone to an
[online document] or [web document] that has an email from Dr. Beaker with
further instructions to find a formula for virus treatment and break into
her private lab.

{{% example font="normal" %}}
**From:** Dr. Susan Beaker <<susan.beaker@cyberdyne.gov>>  
**To:** Virus Research Team  
**Subject:** Please help

---

Good job! You have reestablished my connection to our communication and
research notes. Since General Halftrack isolated me 3 days ago, I have
been desperate  for help.

To start, I need you to find the formula to the virus treatment that I
developed merely 2 day before I left for this emergency trip. Sensing
danger, I locked away my notes, and it appears I was right to do so. I
cannot give you instructions directly over this insecure channel, but you
are clever and I know you will figure it out.

Next, I need you create a secure cryptographic link to me so that we can
talk more freely. This can only be done from within my private lab. My lab
is locked, so you will have to break in.

These 16 weeks on the road have been exhausting, and I'm so glad to be
able to talk to you again.

--Suzzy
{{% /example %}}

[QR fold-in]: /puzzles/qr-construction/fold-in/
[online document]: /equipment/internet/#online-documents
[web document]: /equipment/internet/#web-site-builders


## Getting the Formula (Box 2)

Per Dr. Beaker's email, the players need to find the formula for treatment.
Because the email is not secure, Dr. Beaker cannot overtly say how to get
the formula. But the email contains a hidden code that is used to open a
box revealing some of Dr. Beaker’s lab notes containing the formula (and
multiple other items used later).

**Suggested puzzle:** Dr. Beaker's email contains a [hidden message] with a
code to the box containing her formula. The previously shown message fits
will with the [number words] puzzle. [This online
document](email-help-easier.html) can be a target for this puzzle. For a
more challenging puzzle (with less obvious numbers), [this document can be
used](email-help-harder.html).

Once open, the box contains lab notes describing a formula Dr. Beaker has
been working on such as this.

{{% example %}}

Lab notes of Dr. Susan Beaker

We have made good progress on a formula to reduce respiratory infection in
patients. The compound includes the following elements.

* Vanadium
* Indium
* Carbon
* Iodine
* Cobalt

The formula is currently unstable, but we have high hopes to stabilize the
compound.

{{% /example %}}

[hidden message]: /puzzles/hidden-messages/
[number words]: /puzzles/hidden-messages/number-words/


## Finding the Doctor's Stash (Box 3)

Dr. Beaker has hiding a secret stash of "oregano." She has also misplaced
some critical items that the players need with this stash, so they will
have to find it.

**Suggested puzzle** The [crossword lookup] puzzle works well here. The
crossword itself can be simply found in the room as something someone
randomly left. A player can solve the crossword while others solve other
parts. You will likely need to create a custom crossword to match some
sequence of items in the room.

The resulting code opens a box containing some items required for later
puzzles. I personally also place a small baggie of oregano, which has no
practical value but adds some humor.

[crossword lookup]: /puzzles/paper-and-pencil/crossword-lookup/


## The Doctor's Lab (Room 2)

According to Dr. Beaker's email, the players need to break into the lab.
The lab is a second room behind a locked door. The players will have to
solve a puzzle to unlock the door to this room.

The room itself should be themed like a laboratory. It can have props like
flasks and tubes that are reminiscent of a lab. More puzzle pieces and
boxes are placed in this room.

**Suggested puzzle** The [stick word grid] puzzle can be used here. The
sticks can be hid in box 3 and/or others, and the formula gives the
arrangement of the sticks. In the example of the formula above, players can
translate the names of the elements and convert them to element symbols. (A
periodic table should be provided for reference.) I used the list of
symbols above to arrange the sticks below to reference a page in a book I
happened to have on my bookshelf. (A note with the code for the door was on
that page.)

{{< example-image src="/puzzles/arrangement/stick-word-grid/sticks-vertical-adjust.jpg" >}}

The sticks in this arrangement make for a challenging puzzle. It could be
made easier by underlining the symbols that should be ordered. It can also
be simplified (in terms of both creating and solving) by placing the
element symbols on the top of the sticks and writing any message below
them.

[stick word grid]: /puzzles/arrangement/stick-word-grid/


## Flow Diagram

The materials and suggested puzzles of this escape room follow the
following flow diagram.

{{< mermaid align="center" >}}
graph TB;
  R1[Room 1: Office Space] --> B1(Box 1: Reestablish Email) & B3(Box 3: 'Oregano' Stash)
  B1(Box 1: Reestablish Email) --> B2(Box 2: Getting the Formula)
  B2(Box 2: Getting the Formula) & B3(Box 3: 'Oregano' Stash) --> R2[Room 2: Lab]
{{< /mermaid >}}
