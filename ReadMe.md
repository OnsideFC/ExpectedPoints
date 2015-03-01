### ExpectedPoints

> Calculating Expected Points from bookmarkers' odds

##### Methodology for the calculation of the expected points

1. Take the (decimal) odds of the three possible results of each match.

2. Divide 1 by each of the odds in order to get the chance of each result.

3. Sum these as the bookmakers will have built in a profit so the calculated
chances will add to more than 1 (in this case the figures we get show that the
bookmakers’ profit is around 7 to 8%.

4. Divide each of our original chances (from step 2) by the sum of the three
chances for each match in order to ensure that the chances of the three
possible results add up to 1.

5. Calculate the expected points by multiplying the win and draw chances for
each club by 3 and 1 respectively.


By @SimonGleave 

Url: https://scoreboardjournalism.wordpress.com/2012/09/01/how-to-avoid-rank-journalism-a-simple-expected-points-model/

##### Data

using data from football-data.co.uk for the results, fixtures and betting odds. We have used Bet 365 (B365) for the odds in the football data files.

Presumably in real world or publishable data you would average the odds from all the available bookmarkers in the file to have a fairer reflection of the odds and therefore expected points

##### Demo

See the attached demo.csv whereby we have applied the above methodology to some premier league results, showing the working out and then the total expected points per game for the home (xPTSh) and away team (xPTSa)

