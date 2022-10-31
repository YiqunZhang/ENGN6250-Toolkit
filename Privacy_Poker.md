# Privacy Poker

## Introduction

## Preparation

### Participants

- All developers, product managers and planners. They will learn about the user's understanding and requirements for privacy in this game.
- Some volunteer users, Recommend no less than 10 people. They will express their understanding and request for privacy in the game.
- A host

### Game Kit

#### Poker

We needed some poker cards to play as props. First, the development team needs to determine how much private data will be used in the software, we use $A$ to represent it. For example, `Phone Number`, `Address` and `Name` are $3$ types of private data, $A = 3$.

Then we need to know how much volunteer users will play the games, we use $B$ to represent it. For example, there are $15$ volunteer users, $B = 15$.

We need to prepare $(B+1) \times A$ poker into $B+1$ groups, $A$ in each group, each group is the same. You can find poker image in the appendix and print them on A4 paper. Finally, take out a set of pokers, write down the privacy required by a piece of software on each poker, and do the same operation on each set of poker.

#### Basket

We need 7 baskets, there are labels on each basket. The label is `Necessary Public`, `Necessary Non-public`, `Unnecessary Non-public`, `Unnecessary Non-public`, `Cannot be used`, `Can be used Non-public` and `Can be used Public`. The label can be downloaded in the appendix and you can print them on A4 paper.

## Process

1. Host separates volunteer users from development team
2. Put the baskets with `Necessary Public`, `Necessary Non-public`, `Unnecessary public` and `Unnecessary Non-public` in front of the development team. Put the baskets with `Cannot be used`, `Can be used Non-public` and `Can be used Public` in front of volunteer users.
3. The host distributes poker. The development team gets a set of poker, and each volunteer user gets a set of poker.
4. The development team puts poker into its basket based on different privacy data.
  - Necessary: The software must use this private data, otherwise the software will not be available.
  - Unnecessary:
  - Public:
  - Non-public:
6. The volunteer users puts poker into its basket based on different privacy data.
7. The host counted the poker in the basket in front of the development team and the poker in the basket in front of volunteer users.
8. Statistics of private data with inconsistent understanding between the two sides.
9. For privacy data with inconsistent understandings, such as developers who need to disclose but users do not want to disclose, please explain the reason.
10. Summarize.

## Conclusion

## Appendix

[Poker File](appendix/Poker.pdf)

[Label File](appendix/Label.pdf)
