# Introduction

Sometimes you just don't have a pair of dice and a shoe box to generate your passwords. To cover that need, `diceware` was born. `diceware` is a small utility to generate [diceware](http://world.std.com/~reinhold/diceware.html) style passwords.

## Installation/dependencies

Just download `diceware` and make sure you have the following utilities installed:

* `hexdump`
* `grep`

`diceware` uses `/dev/urandom` to gather the random bytes it needs to pick the words from the word list. All the above should be available on any (modern) UNIX machine.

A word list can be downloaded from [the EFF](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt). `diceware` only supports word lists with 7776 words on it (5 dice rolls).
