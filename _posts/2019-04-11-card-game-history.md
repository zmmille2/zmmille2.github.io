---
layout: post
title: "Might, Magic, Money"
date: 2019-04-11
---

## Disclaimer

I wrote a little about this a while ago in [this post](https://zmmille2.github.io/blog/2018/05/20/might-money-magic), but I wanted to delve into this topic more fundamentally, and to cover what exactly has changed as we went on.
The timeline for a lot of this is very rough, and this is mostly based on my memory.
I also reserve the right to go back and amend this to be totally accurate.
If I take out some bit that you really like, feel free to take it up with this blog's [git history](https://github.com/zmmille2/zmmille2.github.io/commits/master).

It might be useful to have an understanding of what the rules look like now.
Given this is constantly changing, I'll choose to put that at the end, and to constantly update the last paragraph.

### First Steps
Anyways, when we started, we had only a rough idea of what things might look like.
We actually didn't have a firm win condition for a long time.
At first we just investigated the core flow.
It looked something like **Draw Cards/Play Tiles** → **Play Actions** → **Play Units/Traps** → **Resolve Battles** → **Buy Cards**.
This is really similar to what we ended up with as the core flow of the game as it stands today, which is neat.
We would just play rounds of the game until we got bored, and then write down what seemed strong, weak, might be neat, etc.
None of that has anything to do with the way you win, though.

### The Palace
The game is all about fighting over tiles, and we wanted the win condition to reflect that.
We had a special tile that was always in play called the Palace.
<img src="/media/palace.png" alt="The palace tile" title="The palace tile"/>
The palace was guarded by 3 Palace Guards.
<img src="/media/palace guard.png" alt="The palace guard card" title="The palace guard card"/>
Palace guards got weaker as the game went on, 
If you won the Palace on any round, the game was over.

There were a few problems with this setup.
First of all, wins could be very sudden, which is annoying in a deck builder.
You're chugging along building your army and before you get moving some jackass is sitting on the throne.
On top of that, it's very swingy.
If someone gets a very good hand, and you get a very bad hand, that single draw can lead you to losing the game.
We recognized that the Palace needed to change after I put 2 early versions of Dragon on it, leveraging a card called Purge to speed up deployment.
But we didn't know what that fix would be for a while.

### Trap Cards
Next, we had these trap cards.
<img src="/media/trap.png" alt="A trap card" title="A trap card"/>
They weren't units, but they acted like units.
You could lay traps instead of playing units, but your opponents would be none the wiser.
The idea was that there might be a tile you had no interest in, but your opponents were fighting over pretty heavily.
There were a couple of problems with this.
First of all, traps couldn't win tiles.
This made buying traps pretty unattractive unless you were really kicking ass.
Players would buy traps when they were ahead and just sabatoge anyone trying to catch up.
Matt loved the idea of being able to do some subterfuge, but eventually we realized that we could get subterfuge without traps, so they were cut relatively early on.

### Action Cards
Purge from that last section was an Action Card.
Here's Purge.
<img src="/media/purge.png" alt="Purge card" title="Purge card"/>
I liked this card quite a bit, I like trashing in deck builders, it can make your deck feel much stronger by removing the bad.
But the mechanics of the card don't matter too much here.
Remember that flow from earlier?
> **Draw Cards/Play Tiles** → **Play Actions** → **Play Units/Traps** → **Resolve Battles** → **Buy Cards**.
There's a whole part of a round devoted to playing actions.
Even worse, when players start out, they don't have any actions.
So, this part of a round is usually skipped, and once people get used to it, it was really hard to get them to stop and remember that people might have actions to play.
There were some actions that we had that we really liked, though.
<img src="/media/wishing_star.png" alt="Wishing star card" title="Wishing star card"/>
But we found that we could turn these into units.
<img src="/media/fortune_teller.png" alt="Fortune teller card" title="Fortune teller card"/>
We didn't make this change until after we got rid of Traps, for some reason, but once we made this change it immediately felt right.

### Win Condition

We didn't figure out the win condition for a long time.
Even now, I think we've settled on it, but I'm not actually 100% sure this is what we'll end up with.
Just a couple play sessions ago some folks testing it brought up a great idea which has kinda been in my head as a possibility, but for now I'll just talk about where the game has been.

I talked about the Palace early in the post because it was such a cornerstone of the game for such a while.
It was hard to imagine winning any other way.
The biggest strengths of the palace were that it was exactly like normal gameplay and it was so easy to explain because of that.
Seeing if someone was going for the Palace was pretty easy too.
That said, it was hard for folks to team up to defend it.
Temptation to conquer all the surrounding lands while two bozos duked it out in the Palace was too strong for a lot of players, and we saw more than a few games that ended in disappointment and anger because one player tried to play it too greedy.

We talked about other things being win conditions, but coming up with different ways to win that don't just heavily reward one way of playing was really hard.
A natural way to win was to collect tiles, but that punished cards like Supply Line and Thief, that might get you influence without having to win tiles.
<img src="/media/supply_line.png" alt="Supply line card" title="Supply line card"/>
<img src="/media/thief.png" alt="Thief card" title="Thief card"/>
