# mtgpve
MTG Player vs Environment

The idea is to try and build a Turing Engine that can play a game of Magic the Gathering.

But represented in a deck of cards...

Thus there are symbols to be interpreted in a step-by-step fashion.  However, Magic is a complicated game (in fact, it is THE most complex game https://arxiv.org/abs/1904.09828).  I'm not trying to build strategy, just make the source of each possible option determinable by reference to a short set of instructions which are modified by individual program cards.

To do this, I need to create some symbols that are more precise representations of Magic language, such as "land card", "mana value less than four", and "play".  The project starts with me using C# drawing tools to build these symbols programatically before I can use them.

Thankfully there is a font created by Andrew Gioia (https://mana.andrewgioia.com/cheatsheet.html) which does all of the heavy lifting.  Many MTG phenomena have symbols already created.  I'm really just 'filling in some gaps'/

# Phase 1
A console application to create and manipulate MTG symbols



