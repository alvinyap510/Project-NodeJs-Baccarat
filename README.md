# Project-NodeJs-Baccarat

## Introduction

This is a simple NodeJs implementation of the Baccarat game, which is a part of our [Hackathon Project at ETHKL2023 Hackathon](https://github.com/jasonkwm/leo-zakkarat).

On the Hackathon, the Baccarat logic was further moved on Aleo's Blockchain using the Leo programming language.

Thought of would just share the original version of it here.

## How to run

Git clone the repo and run the following commands:

```shell
node src/baccarat.js
```

## Notes

- The Deck class has some advanced functions such as hashing the deck state before game dealing, and reverse verifying the authenticity the game sequence with the provided sequence and salt. Can be further expanded to be something on-chain for verification etc.
