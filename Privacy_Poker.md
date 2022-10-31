# Privacy Poker

## Introduction

Privacy poke is a group game based on developers and users. In this team activity, the facilitator does the moderating. The developer gives the user a brief background knowledge introduction and lets the developer choose the information to collect. It takes the form of a simple game where a number of choices are made by picking different small cards in different baskets. This team game introduces privacy and security, data storage and protection. The game offers a simple way to collect and obtain results by drawing pieces of paper to simulate the user's psychology. Participants of the game can also comment and discuss by taking part in the game, seeing, and evaluating the strengths and weaknesses of the developer's project from their point of view.

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

We need 7 baskets, there are labels on each basket. The label is `Necessary Public`, `Necessary Public`, `Unnecessary Non-public`, `Unnecessary Non-public`, `Cannot be used`, `Can be used Non-public` and `Can be used Public`. The label can be downloaded in the appendix and you can print them on A4 paper.

## Process

1. Host separates volunteer users from development team
2. Put the baskets with `Necessary Public`, `Necessary Non-public`, `Unnecessary Public` and `Unnecessary Non-public` in front of the development team. Put the baskets with `Cannot be used`, `Can be used Non-public` and `Can be used Public` in front of volunteer users.
3. The host distributes poker. The development team gets a set of poker, and each volunteer user gets a set of poker.
4. The development team puts poker into its basket based on different privacy data.
  - Necessary: The software must use this private data, otherwise the software will not be available.
  - Unnecessary: It is possible for the software not to use this private data, but it may make the software difficult to use.
  - Public: This privacy data will be made public.
  - Non-public: This privacy data will not be made public. Only this user and the software development team can know.
5. The volunteer users puts poker into its basket based on different privacy data.
  - Cannot be used: I don't want software to get this privacy data.
  - Can be used Public: I would like the software to get this private data, and it can be made public.
  - Can be used Non-public: I would like the software to get this private data, and it can not be made public.
6. The host counted the poker in the basket in front of the development team and the poker in the basket in front of volunteer users.
7. Statistics of private data with inconsistent understanding between the two sides.
8. For privacy data with inconsistent understandings, such as developers who need to disclose but users do not want to disclose, please explain the reason.
9. Summarize.

## Conclusion

In general, given the context of tracking the corona virus, the project uses poker, a tool known to all, to define the different roles of stakeholders and privacy, government and the general public through the operation and explanation of the development team and the process of starting a game for each person. To observe and capture the user's understanding and requirements for privacy. The logic of the game was constructed using different baskets containing different nature of notes. At the same time, the behaviour of each participant is captured. At the end a framework is proposed that asks all developers and users to think deeply about the advantages and disadvantages of the project, and through analysis and understanding to be able to address and upgrade the current project. Finally, Privacy Poker is a group game that helps developers to understand what users think, allowing project teams and researchers to collaborate with users to get the data that developers want through the game process, to analyse it and draw conclusions, and ultimately to improve and innovate in order to optimise a project that will satisfy the majority of people.

## Appendix

[Poker File](appendix/Poker.pdf)

[Label File](appendix/Label.pdf)
