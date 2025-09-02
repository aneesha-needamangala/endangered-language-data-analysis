# endangered-language-data-analysis
My project utilizes the Abrams-Strogatz model to quantitatively assess the historic decline of the indigenous Hawaiian language, 'Ōlelo Hawai'i, and to predict its long-term stability and survival based on societal factors.

## Background
As the Abrams-Strogatz model assumes, two languages in a given society compete for speakers. The Abrams-Strogatz model thus proposes a differential equation to describe this dynamic between language X and language Y:
\[
$\frac{dx}{dt}$ = (1 - s)(1 - x) ^ (a - 1)
\]

where:
\(x\) = proportion of speakers of language X
\(y = 1 - x\) = proportion of speakers of language Y
\(s\) = prestige of language X (prestige of language Y is (1 - s))
\(a\) = volatility parameter, representing how quickly speakers switch between languages

This project simulates the Abrams-Strogatz model to visualize the competition between 'Ōlelo Hawai'i and English over time, and to graphically represent the resurgence in speakers of 'Ōlelo Hawai'i.

## Features
- Implements the Abrams-Strogatz differential equation
- Produces time-series plots showing the decline and resurgence in speakers of 'Ōlelo Hawai'i

## Methodology
- This model is implemented in Python using numerical solvers for differential equations
- Historical and modern data on 'Ōlelo Hawai'i speaker populations are taken from public online databases to be used in the model
- Took into account governmental recognition, educational accessibility, media presence, and community/daily use to calibrate the prestige factor, \(s\)
