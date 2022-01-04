# Analysis of Kickstarter Campaigns
##### Analysis of Kickstarter data to reveal trends for planning successful theater-related Kickstarter campaign

## Data Overview
Extensive data available. For this analysis project, data provided substational information to shape possible future Kickstarters.

## Limitations or Roadblocks
Data generally well formatted. Some columns broken into categories and subcategories for easier sorting.  UNIX dates converted.

Data contains half a dozen or so Kickstarters I'd consider outliers - either with bad data or over-the-top goals. Mot outliers Kickstarters canceled or failed with $0 donations and/or 0 backers, making the whole project suspect.  Heavily skews raw data.

---

## Analysis of Theater Kickstarters
Based on the data, the vast majority of theater Kickstarter campaigns were 30 or 60 days in length.  Though pedestrian logic may conclude that the longer the project, the greater chance for success, my analysis shows somewhat the opposite.  The more successful theater Kickstarters averaged 30 days in lenght or less.  This can possibly be attributed to top-of-mind donations at the start of a Kickstater, general excitement in the project, and/or fully tapping the donation base quickly.
![Outcome by Length of Kickstarter](https://i.postimg.cc/mrKsTX6h/Outcomes-vs-Length-of-Kickstarter.png)

While the vast majority of canceled Kickstarter theater projects - around two thirds - had no donations at all at the time of cancellation, the rest had recieved at least partial funding.  Over 7% of the projects had received funding in excess of 50%. Using this information, I can concluded that cancellation doesn't necessarily represent lack of interest in the project or lack of funding.

|Percent Funded|Projects Canceled|Percentage of Canceled|
|---|---|---|
|0% Funded|37|68.5%|
|1% to 9%|10|18.5%|
|10% to 49%|3|5.6%|
|50% to 99%|4|7.4%|
|100% or More|0|0.0%|

### Outcomes by Launch Date
Using the data provided, some quick conclusions are that the most successful theater Kickstarters are launched in late spring through the summer months.  While the number of failed projects also increases slightly in the same period, that can be attributed to the overall increase in number of projects.

The success rate of theater projects overall remains fairly high, with the exception of projects launched in December, likely due to individuals' refocus of funds onto the holidays versus any Kickstarter projects.

Chance of a theater project's success remains relatively good across the year.  With the exception of December, chance of success is in excess of 50%.
![Outcomes by Launch Date](https://i.postimg.cc/TYLZQqkc/Theater-Outocmes-vs-Launch.png)

||Percent Successful|Percent Failed|
|---|---|---|
|Jan|58.33%|34.38%|
|Feb|62.83%|34.51%|
|Mar|60.87%|35.87%|
|Apr|62.83%|35.40%|
|May|66.87%|31.33%|
|Jun|65.36%|32.03%|
|Jul|63.04%|36.23%|
|Aug|58.54%|38.21%|
|Sep|60.82%|35.05%|
|Oct|56.52%|43.48%|
|Nov|61.36%|35.23%|
|Dec|49.33%|46.67%|
[^1]

### Outcomes Based on Goal
Outcomes based on overall Kickstarter goal is a partial tale.  Overall the chance of success of a theater project decreases as the goal request increases.  This is easily recongnized the the precipitous decrease in success as the goals push $30,000.  The jump in success in the $35-$45,000 range seems out of place, but further analysis shows a large portion of those projects are real estate related - buildings, space, etc.  Success in these areas indicate individuals are likely to support buying a building for this goal range, but may not be as willing to support individual theater projects.
![Outcomes Based on Goal](https://i.postimg.cc/mZ6vQ6SD/Outcomes-vs-Goals.png)

Further analysis shows a possible area to increase the chance of success is to concentrate more on average donation, versus overall goal.  Successful Kickstarter campaigns earned approximately 138% of the average donation of a failed campaign.  By getting individuals to donate more, the Kickstarter has a much better chance of making goal.

|Outcome|Avg Donation|
|---|---|
|successful|$84.17|
|failed|$61.63|
|canceled|$39.81|


### Limitations
Projects presented with multiple different currencies. Treated all projects as USD for general analysis, but should be properly converted for drilled down apples-to-apple comparisions.


[^1]: Chart excludes projects that were cancelled or live at the time of analysis.
