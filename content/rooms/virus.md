---
title: "Virus"
date: 2022-07-01T20:39:27-06:00
weight:
thumbnail: "virus.png"
summary: "A new virus outbreak is becoming the next pandemic. Your team must work quickly to avert a world-wide disaster."
---

## Scenario (First Room: Office Space)

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
research notes. Since General Halftrack isolated me three days ago, I have
been desperate  for help.

To start, I need you to find the formula to the virus treatment that I
developed merely one day before I left for this emergency trip. Sensing
danger, I locked away my notes, and it appears I was right to do so. I
cannot give you instructions directly over this insecure channel, but you
are clever and I know you will figure it out.

Next, I need you create a secure cryptographic link to me so that we can
talk more freely. This can only be done from within my private lab. My lab
is locked, so you will have to break in.

These sixteen weeks on the road have been exhausting, and I'm so glad to be
able to talk to you again.

--Suzzy
{{% /example %}}


## Flow Diagram

The materials and suggested puzzles of this escape room follow the
following flow diagram.

{{< mermaid align="center" >}}
graph TB;
  R1[Room 1: Office Space] --> B1(Box 1: Reestablish Email) & B3(Box 3: 'Oregano' Stash)
{{< /mermaid >}}


[QR fold-in]: /puzzles/qr-construction/fold-in/
[online document]: /equipment/internet/#online-documents
[web document]: /equipment/internet/#web-site-builders
