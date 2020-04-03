# F1 Fantasy 2020


## Overview:
* Webscrape historical result data (qualifying, starting grid, race results) from [F1 website](https://www.formula1.com/en/results.html).   
* Calculate driver/constructor points based on [fantasy points scoring](https://fantasy.formula1.com/points-scoring).
* Apply [mixed integer programming (MIP)](https://developers.google.com/optimization/mip/integer_opt) to choose 2020 team based on 2019 points.

## Fantasy Rules:
<p align="center">
  <img src="imgs/Select_Team.png" width="400"/>
</p>

1) Pick a team of 5 drivers and 1 constructor from a $100m budget. 
2) You must also select a Turbo Driver for each race who will score double points.
3) Only drivers priced at under $20m can be selected as your Turbo Driver.

Extra: 

* There are no restrictions on how many drivers can be used from a particular team.
* Turbo driver can be different for each race, but must be selected prior to saving your team and doesn't count as a substitution. If your Turbo Driver's price increases to above $20m after you have selected them as your Turbo Driver you can keep them as your Turbo Driver.

For the details see [detailed games rules](https://fantasy.formula1.com/game-rules).
