# Gender Bias in Music: Exploring Spotify's Recommendations
#### Janine Ecker, Łukasz Kaźmierczak, Anna Padiasek, Sophie Shanshory

## Table of Contents
[1. Introduction](#introduction)

[2. Literature Review](#litreview)

[3. Data Collection and Methodology](#method) 

[4. Results and Analysis](#results)

[5. Challenges and Limitations](#limits)

[6. Conclusion and Recommendations](#concl)

[Bibliography](#bibl)

<a name="introduction"></a>
## 1. Introduction

#### 1.1.
<p align="justify"> 

#### 1.2.
<p align="justify"> 




<a name="litreview"></a>
## 2. Literature Review

#### 2.1.
<p align="justify">

#### 2.2. Podcast Recommendations
<p align="justify"> 

<p align= 'justify'>
Given the complexity of algorithmically-generated music recommendations and the impossibility of reaching Spotify’s “black box”, we decided to look closely at how algorithms shape podcast recommendations. This is especially relevant given the increased demand for podcasts in recent years and the growing share of Spotify’s revenue coming from this stream (Majidi, 2023; Casanova). Furthermore, the issue of how algorithms shape users’ podcast preferences remains relatively unexplored. A secondary, compounding “black box” potentially exists for podcast recommendation algorithms. We do not know to what extent recommendation systems for music and podcasts are distinct. This is because the way people listen to and share podcasts differs from these patterns concerning music in two primary ways. 

<p align= 'justify'>
Firstly, regarding virality. Unlike music, podcasts struggle to achieve viral fame due to their lengthy format. Sharing recommendations becomes less effective when listeners can't as easily consume the entire episode as they would a song or even album. Secondly, podcasts and songs have different listening patterns. Once a user finishes listening to a certain episode, they rarely return to relisten it again (Rosenborg, 2024). Furthermore, recommendations can differ by platform. For example, Apple Music recommends shows to listeners, while Spotify recommends episodes (Misener, 2022). (Note that users on Spotify can view generalized music and podcast recommendations at the top of their homepage, but the emerging categories/groupings of recommendations based on user listening patterns include categories such as “Episodes for you” and “Popular with listeners of [podcast name],” which recommend specific episodes rather than a full show.)

<p align= 'justify'>
As mentioned, podcasts and podcast recommendation systems are far less studied than those for music recommendations. In 2020, Nazari et al. explored cross-domain podcast recommendations for “cold-start users” through their music listening history. They claim to be one of the first studies to focus on podcast recommendations. Notably, this study was a collaboration between Spotify and researchers at Cornell University. Nazari et al. studied interference techniques while considering possible emerging biases that music data as an input source could introduce. They define a cold-start problem as “the challenge of making recommendations for users with little to no prior history with the service or medium.” Nazari et al. then tested a cross-domain methodology, using historical interaction data with other media (i.e., music) to produce podcast recommendations. The researchers found that their best-performing model suggested less homogenous recommendations across different podcast categories compared to the popularity baseline system (Nazari et al., 2020). Other literature on podcast recommendations has focused on targeting users’ aspirational consumption through recommendations and predicting user preferences through classification systems (Yang et al., 2017; Tsagkias et al., 2009).

<p align= 'justify'>
It is also worth mentioning other research and analysis of podcast recommendations outside of the academic space. A study conducted by Bumper, a company describing itself as a “podcast growth agency,” mapped Spotify podcast recommendations by gathering episodes of “charting” shows as well as the following six recommended episodes (capturing the six recommendations was repeated twice). Approximately 14% of recommended episodes were Spotify originals or exclusives. Interestingly, Bumper found that Spotify did not promote controversial podcast host Joe Rogan’s show The Joe Rogan Experience despite it being a high performing podcast that is regularly featured on the “Top Podcasts” charts (for reference, on 15/5/24, Joe Rogan’s podcast was at Number 1 on the list in the United States.) This discovery coincides with some of the discourse about which podcasts go viral online: “Many interview-based podcasts from the so-called manosphere have perfected the clickbait formula by figuring out that controversy generates engagement and increases their recommendation positioning on social media platforms and YouTube.” While the non-viral nature of podcasts “on-platform” relates to recommender systems lacking robustness, outside of platforms like Spotify, “off-platform” virality can still occur – for example, if a video of an episode trends on other social media platforms like TikTok or YouTube. However, success off-platform does not necessarily translate to creating more podcast streamers on-platform, especially when users can access snippets from an episode elsewhere. (Rosenborg, 2024) Such an approach to off-platform promotion may have implications on understanding podcast recommendations if we are able to one day more deeply investigate how podcast recommendation algorithms weight popularity compared to user preferences.

<p align= 'justify'>
Finally, does the apparent success of highly-gender podcasts from the manosphere have implications on gendered recommendations more broadly? Because there is little research about podcast recommendations, and none that we could find about gendered recommendations, there is significant space to investigate how recommendations may fall along gendered lines due to a host of factors such as the gender of the listener as well as cross-domain listening history, podcast marketing and brand imagery, popularity, etc. We will seek to build upon these ideas in the coming sections.

<a name="method"></a>
## 3. Data Collection and Methodology

<a name="results"></a>
## 4. Results and Analysis


#### 4.1. Results on the gender bias in Spotify music recommendations.

<p align="justify"> 
On examining the Discover Weekly Playlists recommended for the four accounts after two weeks of listening to the New Music Friday playlist, the vast majority of songs (26 of 30 songs) in the playsts overlapped. It is thus impossible to state whether the differences observed had any significance and were influenced by the gender assigned to each of the accounts. Due to the design of the experiment, such that only one account per each gender category was created, no intra-gender comparison could be made, to state if such differences are not random. Therefore, we have decided to discontinue the analysis of music recommendations. No differences in Spotify music recommendations were furthermore noted, on listening to the specifically curated playlist (“My Playlist #1”). Future research could build upon this design barrier, using multiple accounts of the same gender to confirm our initial hypothesis.

#### 4.2. Results on the gender bias in Spotify podcasts recommendations.

<p align="justify"> 
“Feeding” the Spotify podcasts recommendations’ algorithm took time for all four accounts, with at least three listening sessions needed to receive recommendations related to the content of the podcasts we had listened to. This lag can likely be explained by the previously mentioned “cold-start problem” because the recommendation system lacked a robust music listening history (and had no podcast listening history whatsoever) to begin building its recommendations on. Spotify did not have significant data off of which to base personalized recommendations. (Potential responses to this problem by recommender systems include onboarding (presenting options to a user and asking them to rank their preferences; scraping online information about a user; and updating suggested content based on user ratings) (Nazari et al.).  The category monitored (“Recommended Podcasts”) always contained nine podcasts recommendations for all accounts tested, with the recommendations changing daily (see Figure X for an example). Each time, apart from the data gathered on 23rd April 2024 which reflect the initial podcast recommendations, the recommendations data were gathered after a listening session, to account for a possible stagnation of recommendations of the account due to lack of consistent listening activity. That is because the accounts were only used for podcast listening sessions of up to 3 hours long.

##### 4.2.1. Changes in numbers of stereotypically female podcasts recommended for the accounts over time.

<p align= "justify">
Our findings suggest that there exists a disparity in the speed of Spotify podcasts recommendation of stereotypically female podcasts, depending on the gender of the user. As such, gender stereotypes may thus influence whether a user receives personalised recommendations if the interests of the user go against the stereotypical subjects associated with a given gender. In comparison to accounts associated with “woman”, “non-binary” and “prefer not to say” categories, the “man” account took longer to adjust its recommendations to podcasts classified as stereotypically female (see Figure X). While “woman”, “non-binary” and the “prefer not to say” accounts received between 33-44% of the recommendations as female-coded podcasts after just three listening sessions, the “John Doe” account did so only after four listening activities (2nd May 2024). The account classified as “woman” was the first one to reach almost universally female-coded recommendations, with eight female-coded podcasts recommended out of nine possible recommendations. However, on additional listening sessions, the number of female-coded recommendations for this account dropped, reaching only 6 out of 9 on the last day of the study. 

<p align= 'justify'>
Conversely, even though the account classified as “man” did not begin to receive recommendations as early as the other accounts, after six listening sessions it was the one to receive the most female-coded recommendations - 8 out of 9 possible recommendations were female-coded for this user, on 9th May 2024 as well as on the last day of the study (12th May 2024). The “non-binary” and “prefer not to say” accounts also experienced upward trends in terms of the number of stereotypically-female podcasts recommended to them over time. The “non-binary” account was the least affected account out of four categories tested, receiving a maximum of 66% recommendations coded as stereotypically female. Similarly, the “prefer not to say” account, although steadily rising in the number of female-coded recommendations, received no more than 7 out of 9 recommendations coded as stereotypically female.

##### 4.2.2. Recommendations of specific podcast categories for the accounts.

<p align="justify">
For each podcast recommended, its category labels were gathered. The labels are chosen by the podcast author to describe the main subject with which a given podcast is concerned, and up to 3 labels are available per podcast. Overall, the main category of podcasts recommended among the four accounts was Comedy (72 recommendations), followed by Culture (37) and True Crime podcasts (25). A significant part of the recommendations was focused on personal topics, including Personal Stories (24 recommendations), Self-Help (24) and Health-related subjects (22).

<p align="justify">
For each of the four accounts, the main category of podcasts recommended was “Comedy”. “Culture” was the second biggest category of podcasts for accounts associated with “woman”, “man” and the “non-binary” accounts and the third biggest for the “prefer not to say” account. Surprisingly, “True Crime” podcasts were more often recommended for the “female”, “non-binary” and the “prefer not to say” account than for the male account which instead received recommendations for podcasts related to “Society” issues. “Personal Stories” and “Self-Help” categories were found to be common for all accounts, with the highest numbers recommended for the “prefer not to say” account (10 recommendations per each of the categories). 

<p align="justify">
The high number of “True Crime” podcasts, noticeable for the female account, needs to be analyzed within the context of trends in podcasts popularity among women. While men are more likely in general to listen to podcasts (Riordian, 2018), women consume significantly more true crime media (Vitis and Ryan, 2023; Browder, 2006). Reasons for such behavior according to the literature include the desire to seek justice for victims outside of the legal institutions (Paquet, 2021), the need to gather knowledge on safety precautions in the event of a possible attack (Murley, 2008) or the need of finding a support group of listeners to talk through real-life issues with regard to violence, trauma or assault using podcasts as a starting points for such discussions (Greer, 2017). Therefore, although not accounted as stereotypically female in the study, TCPs can also be seen as a gendered recommendation.

##### 4.2.3. Spotify podcast recommendations of female-hosted podcasts over time.

<p align="justify">
Additionally, we have observed an upward trend in the recommendations of female-hosted podcasts. As the accounts only listened to podcasts created by women, this was expected, however differences were observed in the growth of the number of recommendations skewed towards female hosts. The male account only received a significant number (4 out of 9) of female-hosted recommended podcasts after four listening sessions (2nd May 2024), while for the female and the “prefer not to say account” the Spotify podcasts recommendations included almost solely female-led shows since the fourth listening session (7 out of 9 recommendations on 2nd May 2024). Nevertheless, at the end of the experiment, the majority of the podcasts recommended for all accounts was female-hosted.

<p align="justify">
On looking separately at the accounts, over time the “prefer not to say” account received the greatest number of female-hosted podcasts out of all accounts (60% of recommendations) while 56% of podcasts recommended for the female account were created by women. The share of female-hosted podcasts recommended for the male and “non-binary” accounts was lower, and amounted to 46% and 51%, respectively. This finding suggests that here, too, the gender of the user may have had an impact on the early podcasts recommendations of the users, with users not identified as “male” being more likely to receive recommendations of female-hosted podcasts.

<a name="limits"></a>
## 5. Challenges and Limitations

#### 5.1. Challenges
<p align="justify"> 

#### 5.2. Limitations
<p align="justify"> 

<a name="concl"></a>
## 6. Conclusion and Recommendations

#### 6.1. Conclusion
<p align="justify"> 

#### 6.2. Recommendations
<p align="justify">

<a name="bibl"></a>
## Bibliography
