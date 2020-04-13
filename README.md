# covid19-tweets

Track information dissemination about COVID-19 by local government agencies

Created by Irena Fischer-Hwang (<ihwang@stanford.edu>)

## Project goal

Stanford University's Big Local News project performed basic analysis of Tweets posted by local government agencies in the United States regarding the COVID-19 pandemic.

This notebook pulls in data from a variety of sources including an exported CSV of Tweets, a Google Sheet containing government agency twitter handles, a Google Sheet summarizing shelter-in-place orders for different states and The Covid Tracking project. Data are summarized and displayed in simple plots comparing quantities like cumulative tweets, cumulative tweets regarding COVID-19, retweets, shelter-in-place orders and basic statistics about confirmed COVID-19 cases.

### Staff involved

Simon Willison (<swillison@gmail.com>)

Dilcia Mercedes (<dilcia19@stanford.edu>)

Amy DiPierro (<dipierro@stanford.edu>)

### Data sources

Tweets were downloaded from Simon Willison's [Datasette Cloud](https://corona-tweets.datasettecloud.com/data/tweets)

Lists of local government agency handles were compiled by Big Local team members and accessible via a [Google Sheet](https://drive.google.com/open?id=13wRn7ZswD2p180OQY7JiJgv-CHug36CiQqFkhpzQYwY)

Shelter-in-place ordinance dates were compiled by Big Local team members and accessible via a [Google Sheet](https://drive.google.com/open?id=1iOChy4gxV3RUz2uHYRHL5OwSbyIV8p9Jo1tTR-R1-Hw)

Confirmed positive tests, hospitalizations and deaths from COVID-19 are pulled from [The COVID Tracking Project](https://covidtracking.com/)

## Technical

There are two analysis notebooks. `analysis/explore-tweets.ipynb` provides a template for at-a-glance comparison of Tweets from government agencies in different states. `analysis/state-tweets.ipynb` provides a template for digging deeper into Tweets posted by multiple local government agencies for a single state.

<!--
### Project setup instructions

After cloning the git repo:

`datakit data pull` to rerieve the data files.

Open `covid19-tweets.Rproj` in RStudio.

*TK: For more complex or unusual projects additional directions follow*

## Data notes

*Add important caveats, limitations, and source contact info here.*
-->
