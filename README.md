== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project. We urge you to read about the
[Give up GitHub](https://GiveUpGitHub.org) campaign from
[the Software Freedom Conservancy](https://sfconservancy.org) to understand
some of the reasons why GitHub is not a good place to host FOSS projects.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)


* For 2 users for now

# Stages

1. Enter dice combination of first round
2. Simulate throws of all subsets of dice for remaining rounds
	1. For each open category record probability of occuring from simulations
	here distinguish between one and two consecutive throws for good throws out of possible throws
	for 2nd throw only cound 2nd throw
	for 3rd throw cound 2nd and 3rd throw

for now just one throw ahead: matrix where row is subset of dice and column is entry for category
