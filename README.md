# Videogame-Recommendations-Using-Steam-Data
Recommending videogames to gamers using Steam data from this Kaggle dataset: https://www.kaggle.com/datasets/tamber/steam-video-games/data

![Steam's image](https://cdn.cloudflare.steamstatic.com/store/home/store_home_share.jpg)

## Introduction 

"Steam is the ultimate destination for playing, discussing, and creating games." 
Steam is a digital videogame service developed by Valve Cortporation to provide updates for their games, but expanded to third-party titles in late 2005 from Triple A games to indie games in 2005. It's a very important and trusted in the gaming space, as well as biggest game catalog storefront. 

## Business Problem

According to Steam's latest user data, there are 132 million monthly active users on Steam. With 73,000 videogames, how do you know what recommend each user? Play it safe with the most popular games? What about trending games? Rating wise? 

After seeing many post online about the confusing recommendations and endless scrolling for new games, Steam has tasked me to attempt making a greater recommendation system/improve the current one. 

As far as Steam's current recommendation system (popularity, trending/new, ratings), these aren't bad recommendations as highly praised games are most likely going to be liked by most people, but not _everyone_. Steam also has a content-based rec. system based on tags of games a user has played, but this will be the first user-based one.

## Limitations

In the dataset on Steam data from kaggle, there are no limitations at alll. Its a perfectly clean dataset with exactly 200k rows on users game purchases and playtimes. 

Well, unless the fact that there are 129k instances of purchasing games and only 70,000 of those instances get played across the entire dataset counts as one, but that doesn't affect the dataset and the recommendations at all.

## Analysis

Using the information in the data, I have found out that-

- 12.4k unique users
- 5,155 videogames
- Purchase count is 129.5k,  Play count i 70.4k
- So there is 59.1k instances of purchasing without playing...

Outliers -

- Highest purchase count is 1k (User only played half of their games lol) 
- Highest total playtime is 11.7k
- Most played game has 980k, 2nd most has only 322k


## Visualizations

## Methods

Recommendation System itself pretty much

## Model Visualizations

## Conclusions

## Future Analysis