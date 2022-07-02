+++
author = "Simon Grimm"
title = "Fermi Poker - Instructions"
date = "2022-06-30"
publishDate = "2022-06-30"
description = "How to play a favorite of mine"
tags = [
    "fermi", "bayes",
]
+++

I've recently discovered Fermi Poker, but couldn't find online instructions that I could point others to. Hence, here goes a small description. In a nutshell, Fermi poker consists of making and updating Fermi estimates, that is, guesses about hard but fun questions—such as ‘How many Avocadoes are produced worldwide per year”, or "How many litres of water are there on Planet Earth?".

(Many litres in fact)

<img src="/earth.jpg" alt="A picture of the earth." class="img-responsive" style="vertical-align:middle;margin:0px 0px">


If you're unfamiliar with how to arrive at Fermi estimates you can find a [great explainer here](https://en.wikipedia.org/wiki/Fermi_problem).


_____________
### Preparation

You need a minimum of three individuals to play, six people being optimal.

Before starting to play, each player needs to come up with a question (**Q**), an answer (**A**) and two hints (**H1** & **H2**). The answer should be based on reputable sources, e.g., [Our World In Data](https://ourworldindata.org/), [Statista](https://www.statista.com/), or [Wikipedia](https://wikipedia.org/).

You can find resources for good questions in this [blog post by Chana Messinger](https://chanamessinger.com/blog/fermi-problems). There's also a great Twitter account, publicly solving Fermi estimates every day, with the ingenious name [BOTEC Horseman](https://twitter.com/botec_horseman).

Here are two example questions:

#### Example 1 - Roads in China

> **Q**: How many kilometres of paved road is there in China?
>
> **A**: There is  ~5’200’000 km of paved road in china
>
> **H1**: There are 664’480 km of road in Germany.
>
> **H2**: Vietnam has 6km of road per 1000 inhabitants. (Total Road: 570’448, Total inhabitants: 97’000’000)

#### Example 2 - Replacing the entire sun with nuclear power

>**Q**: How many nuclear power plants, similar to [Hickley Point C](https://en.wikipedia.org/wiki/Hinkley_Point_C_nuclear_power_station) would you need to produce as much power as the sun?
>
>**A**: You would require 1.089375 × 10^17 nuclear power plants.
>
>**H1**: Hickley Point C will produce 3,200,000,000 Watts.
>
>**H2**: The sun produces < 10^30 Watts.


Lastly, you will also need poker chips, in the absence of physical chips you can use [this website](https://pokerchips.io/).

Armed with one question each and a way to allocate chips you can start playing!

_____________

### Gameplay

One round is always based on one question. As the designed of the question knows the answer they don't play, rather facilitating the round:

 1. The authors poses the question. All other players come up with an answer, sending their estimate to the author, e.g., via Signal. Players are not allowed to use the internet or calculator to arrive at the answer.

 2. Going counter-clockwise, the first player always gives a small blind (e.g., 25), the second player gives a big blind (e.g., 50). Following this, players can bet as much as they want, having to match the highest bet just like in normal poker.

 3. After everyone made their first bet, it is the question author's turn again, giving the first hint.

 4. Again going counter-clockwise, players can now update their bets, either increasing, folding, or calling.

 5. Following the players' update, the author gives the second hint.

 6. Again, everyone updates their bet accordingly.

 7. Finally, the answers of everyone who hasn't folded are evaluated. The winner is the person whose log10(difference to the answer) is the lowest. If two people give the same answer, they split the pot. If there is only one person still in play, that person takes the entire pot, without giving their answer.

The game then commences, until all questions were asked.

_____________

### Why should you play this?


**Apart from being fun**, Fermi Poker improves two skills:

 1. It forces one to quickly juggle and combine order of magnitude estimates. This is useful in quickly evaluating numeric claims by others.

 2. You also learn to quickly update your beliefs in the light of new evidence.

Finally, you learn a lot of fun facts about the world!

