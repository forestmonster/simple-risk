---
title: "Strategy"
date: 2021-10-26T13:12:14-07:00
draft: false
menu:
  docs:
    parent: "estimation"
---

Estimation is a skill that benefits from an understanding of known approximation strategies. These mental models will help support common problems in risk modeling, elicitation, and forecasting. They're also useful as elicitation techniques when trying to draw out numeric estimates from an expert.

### Divide and Choose

Divide and choose is a mental heuristic to determine if odds are fair or
not. It is similar to the children\'s \"fairness\" concept:

1. One child slices a piece of cake
2. Another child chooses the slice they\'d like.

Of course, this method prevents the first child from slicing unevenly and taking
the larger piece and forces them to behave impartially to the outcome. Being partial would result in them receiving a smaller slice.

The ability to impartially estimate odds is crucial to forecasting and decision making. Opportunities for advantageous decision making arise when rewards are not congruent with the odds, but the ability to see these impartially can be difficult.

### Principle of Indifference

The [principle of
indifference](https://en.wikipedia.org/wiki/Principle_of_indifference)
is a rule of thumb that divides probability across all of its options.
For instance, two outcomes at 50/50% or four outcomes at 25/25/25/25% respectively.

This principle is similar to the [uniform distribution](docs/estimation/distributions).

When faced with a scenario with four outcomes, this principle suggests starting with 25% forecasted probabilities for each of outcome and continuing a study from there. Assuming there is no available information to suggest one outcome over another, this would be the most efficient default strategy to avoid error.

During an [elicitation](/docs/estimation/expert-elicitation), an expert may immediately disagree with these odds and find themselves confronting information about their beliefs for each scenario. Afterward, it\'s likely that the forecaster has opinions they may express numerically.

### The Absurdity Test

An absurdity test would assigns extreme and irrationally formed likelihoods
or values to a forecast, testing the opinions of a forecaster. For
instance, \"A small child can eat between zero and one million pies in a
sitting.\"

When faced with such a test, a forecaster may be encouraged to start
making a forecast *less* absurd. For instance \"Well, a child can at
least eat half of a pie, and maybe up to five pies, in extraordinary
circumstances.\"

This form of test has been used as an interview prompt in psychological
research since the [1900s](https://www.google.com/books/edition/The_Journal_of_Philosophy_Psychology_and/-zWCoyAWHjMC?hl=en&gbpv=1&dq=%22absurdity+test%22&pg=PA415&printsec=frontcover).

## Inside and Outside Views
Tetlocks books frequently visit the concept of inside and outside views. Let's assume we are measuring how often we'll suffer a major data breach.

**Outside View:** How often do companies in this sector suffer major data breaches?
**Inside View:** What makes this company different than the rest?

This approach to the problem allows you to consider the measurement as a prior and posterior issue. Immediately jumping to an inside view may cause you to focus on vulnerabilities and risks that are recently discussed, rather than how frequently threats may arrive to exploit them. Without that in mind, all your risks may seem like imminent problems.