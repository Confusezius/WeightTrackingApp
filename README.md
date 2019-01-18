## Weighttracking iOS App
This repo contains the setup for a weighttracking app which allows the user to enter their weight at certain points in time. Using Gaussian Process-based Regression (implemented FULLY in javascript - looking back, their might have been smarter solutions), it helps the user by giving short- and longterm trends (linear mean and Ornstein-Uhlenbeck or RBF Kernel) and suggesting caloric in- or output to reach a given target weight.

This is implemented using PhoneGap (https://phonegap.com/), i.e. it fully runs on html with Bootstrap and JQuery, although in either cases using mostly obsolete versions of these libraries.

The purpose of this repo is archival and storing the lowlevel javascript implementation of Gaussian Process Regression.

__NOTE:__ This was done quite some time ago and was set quite ambitiously, however there were simply to many things to adjust before having an app that would make it to the App Store. Nonetheless, many implementations might still be useful for similar future projects

## Impressions
This gif should summarize all the basic app functionalities. However, be warned: The layout is atrocious!
![imp](summary.gif)
