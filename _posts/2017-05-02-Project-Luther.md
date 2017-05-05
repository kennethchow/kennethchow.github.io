---
layout: post
title: A Green Regression
---

The goal for our second project was to practice web scraping and performing a simple regression on our collected data. A choice of a few prescribed topics to research were presented to us; namely sports, beer, or movies mainly because the structure of these websites facilitated the process of scraping i.e. extracting web content. None of the above really piqued my interest so I decided to look into topic that excited me: Marijuana.

## Let's talk about the birds and bud

Marijuana as an industry is very much still in the introduction phase with Colorado leading the pack with legalisation and various other states including California following suit. The opening up of a new industry means a completely empty market with no competition and vast potential for growth in all aspects from everything involved in growing to distribution and even novel products made of the flower.


![Colorado Tax Revenue]({{ site.url }}/images/SR231_1.png)
<em>Fig. 1 Marijuana tax revenue by month from January 2014 to January 2016</em>


Colorado is the gold standard model for the success of Marijuana with steadily growing tax revenue which is representative of the growth of the industry. Over 2016 Marijuana sales revenue across the US increased to $6.7 billion, up 30% from last year. According to research by Arcview Market Research the industry is projected to grow to $20.2 billion, for perspective the domestic alcoholic beverage industry is worth $200 billion.

## Project Luther

Using strain data obtained from [Allbud](https://www.allbud.com/) which included genetics, THC content, positive effects, medical uses and flavors I built a regression model to predict the genetics of a strain using the known traits of said strain. 

  > Cannabis can be classified into two main species: Cannabis Indica and Cannabis Sativa. In scientific nomenclature the first word refers to the Genus - a taxonomic category within which species share similar traits. This has enabled crossbreeding which has given rise to the vast variety of Sativa/Indica hybrids taking different proportions of genetics from parent strains.


![Features]({{ site.url }}/images/featureselection.png)
<em>Fig. 2 Features with the highest contribution to determining genetics according to my linear model</em>


Energizing, Uplifting and Creativity are effects positively correlated with Sativa genetics. Fatigue is also a positively correlated medical use. The 3 traits on the right are negatively correlated with Sativa genetics i.e. positively correlated with Indica genetics.

## An outlook on the future of Green Data

Using a simple python script I gathered data from a website and performed analysis on this to draw a conclusion. With this in mind the following thought progression is that given the availability or the ability to collect data and statistics the applications are endless for an industry showing steady 30% annual growth. Both Data Science and Marijuana are budding fields and I'm eager to find out what's in store. I am thankful to witness and would be enchanted to be part of this transformation.