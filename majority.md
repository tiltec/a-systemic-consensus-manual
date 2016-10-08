# Majority

*What do you want?*

Majority decision making looks to find the option with the most support. It is the first time of genuine group decision making method has been discussed in this manual. All of the majority voting systems at best attempt to aggregate the internal decisions of many individuals. 

Internal feeling: the honest feeling of an individual towards the given options.
External expression: the information transmitted by an individual regarding their feelings towards the options. This can be strongly influenced by what the individual is able to transmit and how this information will be processed.
Expression processing: A determenistic process in which expressions are considered and an option is selected. This typically involves a method for aggregating the information and a decision rule(s).

## Plurality voting ##

*Chose one*

This form of voting is so common that for many it is synonymous with 'voting' itself. Please say out loud to to yourself right now *'plurality voting is only one type of voting system and there are others'.* You know the story, all the options are on the ballot and you get to chose the one you want the most. The votes for each option are counted and a simple decision rule is applied:

* **Absolute majority a.k.a. First past the post (FPTP):** Option with most votes wins (could be much less than 50 %)
* **Relative majority:** Option with more than 50 % wins
* **Supermajority:** Option must have more than 50 % to win. 60 %, 66.6 %, 75 % are all common.
* **Unanimous consensus:** 100 % in favor (a twisted form of consent decision making).

Plurality voting is cognitively pleasing: you're used to it and it's so simple! Everyone says what they want most and we go with the one that most people want. It is precisely this simplicity that is a problem and this manifests itself in many ways. 

The first side-effect is **wasted votes.** Everyone that votes for an option that doesn't win has essentially wasted their vote as it had no impact on the final decision. Another side-effect is the **Spoiler effect:** options that are similar lead to a splitting of the vote, ultimately favoring the selection of more unique options. Both of these effects lead to **tactical voting** where people who are concerned that the option they like best is not likely to win and place their vote for someone else - this is usually to prevent a popular but personally unfavorable option from being selected.

### What shall we do with a drunken sailor? ###

---

|| Abi | Bill | Oscar | Peggy | Blue-eyes | Total
| -- | -- | -- | -- | -- | -- | -- |
| **Barrel-roll** | X |  |  |  |  | 1 |
| **Counseling** |  | X |  |  | X | 2 |
| **Withdraw rum (month)** |  |  | X |  |  | 1 |
| **Withdraw rum (week)** |  |  |  | X |  | 1 |
| **Meditation** |  |  |  |  |  | 0 |

The crew try one-vote-per-ballot with the plurality decision rule to ensure a single option wins. With 40 % support, the crew selected the Barrel-roll. This option is selected even though most of the crew did not vote for it! When they talk about it afterwards, some interesting things are discovered: 

* Blue-eyes guessed no one else would vote for their favored option - meditation. Because of this they voted for counseling because they really didn't want Barrel-roll to win.
* Peggy and Oscar only had a slight preference between withdrawing rum for a week or month and would have both voted for the same option had they known.

## Cumulative voting ##

*Place 5 votes*

In cumulative voting each voter gets a set number of votes that they can place on the available options as they see fit: all votes on one option, divided between 2 options, etc. As for plurality voting, the votes for each option are counted and a simple decision rule is applied, typically FPTP.

You can imagine that it's the same system, except that your single vote has been split into several parts. Using any less than all of them for your favored option is essentially a dilution of your preference. As such cumulative voting suffers from the very same set of side-effects as plurality voting! Wasted votes, the Spoiler effect and tactical voting. 

## Ranked voting ##

*Number options from 1st to 5th*

In ranked voting each voter expresses their preference for each option putting them in order of most favored to least favored. Processing rankings into a decision is not a trivial endeavor and many different decision rules have been created to reach an outcome:

* Single Transferrable Vote
* Borda Count
* Instant Runoff Vote. If there is no relative majority of 1st choices, the least popular option is recounted for 2nd choices and added to first count. If there is still no relative majority, the least popular option is recounted for 3rd choices... etc.
* Copeland's Method
* Schulze Method
* Kemeny-Young Method
* Nanson
* Minimax
* Dodgson
* Ranked Pairs

## Approval voting ##

*Chose as many as you like*

## Range voting ##

*Rate how much you like each*

## Advantages of majority ##
Simplicity

Scalable:

## Disadvantages of majority ##
Trivialization
* War on critics
* Tactical voting
* Losers and winners
* Dragging of losers
* Rule by minority

In a hypothetical ballot with 5 options, the number of ways a participant could express themselves is evaluated in 5 different voting systems:
* Majority vote: $$(No. options)^1 = 5^1 =5$$
* Approval vote: $$2^{(No. options)} = 2^5 =32$$
* Ranking vote: $$(No. options)! = 5! = 120$$
* Cumulative vote (w. 5 votes): $$(No. options + No. votes - 1)! / ((No. options-1)! / (No. votes)!) = 9! / (4! * 5!) = 126$$
* Range vote (8 pt. scale): $$(pts. on scale)^{(No. options)} = 8^5 = 32768$$

| Method | No. possible full expressions | Zero-sum/Non-zero-sum |
| -- | -- | -- | 
| Plurality vote | 5 | Zero-sum | 
| Approval vote | 32 | **Non-zero-sum** |
| Ranking vote | 120 | Zero-sum |
| Cumulative vote | 126 | Zero-sum |
| Range vote | **32768** | **Non-zero-sum** |
