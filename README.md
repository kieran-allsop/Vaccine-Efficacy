# Vaccine-Efficacy

Vaccine-Efficacy cotaines R code in a markdown file that replicates all simulations and calculations in the paper [Awaiting the signal: Assessing the efficacy of COVID-19 vaccines](https://www.aei.org/research-products/report/awaiting-the-signal-assessing-the-efficacy-of-covid-19-vaccines/).

## Overview

The markdown file makes it easy to reproduce all of the calculations in the paper [Awaiting the signal: Assessing the efficacy of COVID-19 vaccines](https://www.aei.org/research-products/report/awaiting-the-signal-assessing-the-efficacy-of-covid-19-vaccines/). In the paper Jim Capretta and Scott Ganz assess the length of time it takes for a vaccine to be approved through Phase III of testing and also assess other vaccine efficacy factors such as probability of success and the statistical power of different lengths of vaccine trials. All simulations in the file are based off of [FDA guidelines](https://www.fda.gov/media/139638/download) for what is considered an effective vaccine. 

## How to use Vaccine-Efficacy

View the code in [vaccine_efficacy_replication.rmd](https://github.com/kieran-allsop/Vaccine-Efficacy/blob/master/vaccine_efficacy_replication.Rmd). This markdown file contains all of the code and includes the part of the paper that that code relates to describing what is happening. Running each section in order will produce the desired simulations. There are sections for false positive analysis, required vaccine efficacy rates, estimating wait times, statistical power, and evaluating intermediate endpoints calculations. The file [vaccine_efficacy_replication.html](https://github.com/kieran-allsop/Vaccine-Efficacy/blob/master/vaccine_efficacy_replication.html) provides the same code and descriptions but in an easier to read format in a html compiler.
