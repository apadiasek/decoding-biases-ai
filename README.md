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

#### 2.1. (Gender) Bias in Recommendations
<p align="justify">
Gender bias in recommendations is a multifaceted issue, influenced by factors beyond the programming of the algorithms. Firstly, there might be a population bias, which occurs when a dataset reflects societal imbalances. If Spotify's dataset overwhelmingly features music by male artists, the algorithm will naturally recommend them more often, even to users who might enjoy female artists equally. Secondly, parameters such as location, time, means of access, etc. might influence recommendations. However, it is interesting to understand what happens when these factors are held constant from a purely algorithmic perspective. In such circumstances, it is necessary to understand what is fair, i.e. why certain songs prevail over others. Transparency is crucial. As Melchiorre et al. (2021) point out, informing users about how recommendations are generated, like saying, “This song is recommended because other female listeners enjoyed it,” can raise awareness of potential bias.

<p align="justify">
Streaming platforms like Spotify face growing concerns about algorithmic bias and discrimination, particularly regarding gender misrepresentation. As Hodgson (2021) argues, algorithms can reinforce existing stereotypes by promoting specific genders within genres. Indeed,  one of the first empirical studies in the field conducted by Eriksson and Johansson (2017) seems to confirm this claim, as they discovered that Spotify recommendations tend to favor male artists across all genres. This perpetuates the general trend in the music industry, which is decades old and emerged even before the rise of streaming platforms. While some suggest algorithms favor male artists, others point to a lack of inherent bias and instead highlight the issue of population bias – a limited pool of songs by female artists on the platform (Aguiar et al., 2018). The debate is still ongoing. Aguiar et al. (2021) further complicate the issue by pointing out that human curation of some playlists contributes to the problem. Therefore, the misrepresentation cannot be purely attributed to AI systems. Nonetheless, features such as “related artists,” “discover,” and “browse”, which are uniquely tailored to the users’ preferences, reinforce ideas about the gender affiliation of artists and songs. Noteworthy, they may invisibly shape users’ preferences. Our study is motivated by the fact that the literature on what drives the potential bias in algorithmic music recommendations remains inconclusive.

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

<p align="justify">
In this investigation, we set out to uncover how the gender of different users may impact Spotify’s algorithmic systems delivery of recommendations. The black box of podcast recommendations proved particularly interesting because it remains underexplored. After creating four unique accounts, each with a different gender, and streaming hours of podcast content, we began to receive initial recommendations. At first, Spotify’s recommendations appeared to face a cold-start problem, lacking sufficient historical music and podcast inputs from which to craft its personalized suggestions. Over the next few listening sessions, however, the “woman”, “non-binary”, and “prefer not to say” accounts received female-coded recommendations earlier than the “man” account, though eventually the latter surpassed the former three and gained the most female-coded recommendations. Further, this lag in initial, female-coded recommendations was mirrored by the lagged recommendations of podcasts hosted by women – most notably for the “man” account –  though eventually all users’ recommendations exhibited an upward trend and the “man” account in fact surpassed the others again. Overall, the changes in recommendations of overtly-female podcasts as well as podcasts created by women were slower for the account categorized as “male”, despite the identical user activity of the accounts. Once the listening activity was established, the male account also received recommendations of topics stereotypically not related to that gender.

<p align= "justify">
Our analysis suggests that the gender of the user may have an impact on the pace of providing podcasts recommendations on the Spotify platform. This impact can be analyzed using various categories, including the topic-specific recommendations or recommendations based on the gender of the podcast creator.

<p align= "justify">
Given these observations, our first suggestion is unsurprisingly for more research to be conducted on podcasts and podcast recommendations systems. It is evident that the (limited) existing research on podcasts and their recommendation systems has overwhelmingly been conducted by stakeholders in the industry – streaming platforms like Spotify themselves or other companies that market themselves as podcast resource/support agencies. This has potentially interesting implications – especially because we still know very little about the unique black box for podcasts. Thus far, the research does not appear to seek to demystify the black box at all, because it is being carried out by the very stakeholders who shield its intricacies. If there were biases uncovered, the players paying for the research would have an incentive to limit some of those details or at the very least maintain the opacity of their algorithmic systems. (This is not to say there is no role for these stakeholders in the research, but they should not be the sole producers of it.) There is a need for more independent research, which could bring us closer to understanding the layers to these recommendation systems and to parse out any key differences between music versus podcast recommendations.

<p align="justify">
Though we were not able to definitively conclude that there are biases in the Spotify podcast recommendation system, the gender of a user could imply how quickly Spotify “corrects” its initial recommendations when it has little else off which to base them. Further, it does appear that Spotify at times “overcorrected” its lagged recommendations with the “man” account, offering more female-coded and female-hosted podcasts later on compared to the other accounts. While the platform may have corrected overtly female-focused content, podcasts focusing on True Crime (which is popular among women listeners and could potentially be coded as gendered content) did not receive the same overcorrection for the “man” account (this account only received a total of three recommended True Crime podcasts). This brings us to our second research-based suggestion: more research on gender and podcasts. On one hand, we encourage future research to examine gender and podcasting along our broad identified criteria – major themes, tone, and marketing. With respect to the latter criterion, our preliminary reflections found the three non-“man” accounts received higher suggestions for True Crime. While some of the positioning of these shows appeared quite neutral, the marketing of other True Crime podcasts appeared visually feminine, with pink branding that mirrored that of the chatty gossip and relationships-focused podcasts which we coded as overtly-female. Secondly, we see a need for research that focuses on the manosphere and its rising appeal and success in the podcasting space. We cannot understand gender on social media without interrogating this emerging cultural and political phenomenon. There is little academic literature focused on the manosphere across all social media platforms, not just within podcasting/streaming. This type of content focuses on men’s feelings of disenfranchisement, often dipping into misogynistic tropes and critiques of socio-political ideologies they see as sidelining men (Rich & Bujalka, 2023). Further, understanding this particular highly popular and highly gendered content on the Internet could shed light on other gender trends, especially when it comes to how other highly gendered but non-manosphere-focused content is recommended and disseminated to listeners.

<p align="justify">
Our findings also illuminate some broad trends about how different categories of podcasts are organized. This is potentially pertinent to gender issues because certain tags could be more or less associated with gender and user characteristics. Building off our initial suggestions, our third suggestion is to improve the categorization of podcasts on streaming platforms. There was highly inconsistent tagging across our podcast recommendations, with some tags being difficult to interpret alongside the podcast show and description (some podcasts had only one tag, some had none at all). If Spotify and other streaming services encourage more consistent tagging/categorization, this could prove to be a helpful tool in understanding how recommendations are made – and possibly to help improve their own preference-based recommendations.




<a name="bibl"></a>
## Bibliography

<p align="justify">
Aguiar, L., Waldfogel, J., & Waldfogel, S. (2018). Playlisting Favorites: Is Spotify Gender Biased? JRC Digital Economy Working Paper 2018-07; JRC Technical Reports, JRC113503.
<p align= 'justify'>
Aguiar, L., Waldfogel, J., & Waldfogel, S. (2021). Playlisting favorites: Measuring platform bias in the music industry. International Journal of Industrial Organization, 78, 102765.
<p align= 'justify'>
Anderson, A., Maystre, L., Anderson, I., Mehrotra, R., & Lalmas, M. (2020). Algorithmic effects on the diversity of consumption on Spotify. Proceedings of The Web Conference 2020. doi:10.1145/3366423.3380281.
<p align= 'justify'>
Björklund, G., Bohlin, M., Olander, E., Jansson, J., Walter, C. E., & Au-Yong-Oliveira, M. (2022). An exploratory study on the Spotify Recommender System. Information Systems and Technologies, 366–378. doi:10.1007/978-3-031-04819-7_36.  
<p align= 'justify'>
Browder, L. (2006). Dystopian romance: True crime and the female reader. The Journal of Popular Culture 39(6): 928–953.
<p align= 'justify'>
Casanova, A. (N.d.). What the podcast boom means for digital revenue in a post-pandemic landscape. FT Strategies. https://www.ftstrategies.com/en-gb/insights/what-the-podcast-boom-means-for-digital-revenue-in-a-post-pandemic-landscape/. 
<p align= 'justify'>
Greer, A. (2017). Murder, she spoke: the female voice’s ethics of evocation and spatialisation in the true crime podcast, Sound Studies 3:2, 152-164.
<p align= 'justify'>
Hodgson, T. (2021). Spotify and the democratisation of music. Popular Music, 40(1), 1–17.
<p align= 'justify'>
Majidi, M. (2023, 13 December). Share of podcast in Spotify’s advertising revenue the United States from 2019 to 2024. Statista. https://www.statista.com/statistics/1324009/spotify-podcast-ad-revenue-share-usa/. 
<p align= 'justify'>
Misener, D. (2022, 22 August). I made a map of Spotify podcast recommendations. Here’s what I learned. Bumper. https://wearebumper.com/blog/2022/08/22/spotify-episode-recommendation-algorithm. 
<p align= 'justify'>
Murley, J. (2008) The Rise of True Crime: Twentieth Century Murder and American Popular Culture, Bloomsbury 3PL.
<p align= 'justify'>
Nazari, Z., Charbuillet, C., Pages, J., Laurent, M., Charrier, D., Vecchione, B., & Carterette, B. (2020). Recommending Podcasts for Cold-Start Users Based on Music Listening and Taste. Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval. https://doi.org/10.1145/3397271.3401101.  
<p align= 'justify'>
Pâquet L (2018) Literary forensic rhetoric: Maps, emotional assent, and rhetorical space in Serial and Making a Murderer. Law and Humanities 12(1): 71–92.
<p align= 'justify'>
Rich, B. & Bujalka, E. (2023, 21 February). The draw of the ‘manosphere’: understanding Andrew Tate’s appeal to lost men. The Conversation. https://theconversation.com/the-draw-of-the-manosphere-understanding-andrew-tates-appeal-to-lost-men-199179.
<p align= 'justify'>
Riordan, K. (2018). Commentary: The mobile phone as the new transistor radio. In: Park S, Fisher C, Fuller G, et al. (eds) Digital News Report: Australia. Report. News and Media Research Centre, University of Canberra.
<p align= 'justify'>
Rosenborg, R. (2024, 10 January). Podcasts have a recommendation problem. MIDiA Research. https://www.midiaresearch.com/blog/podcasts-have-a-recommendation-problem. 
<p align= 'justify'>
Tsagkias, M., Larson, M., & De Rijke, M. (2010). Predicting podcast preference: An analysis framework and its application. Journal of the American Society for Information Science and Technology 61, 2 (2010), 374–391. 
<p align= 'justify'>
Vitis, L., & Ryan, V. (2023). True Crime Podcasts in Australia: Examining Listening Patterns and Listener Perceptions, Journal of Radio & Audio Media, 30:1, 291-314.
<p align= 'justify'>
Yang, L., Sobolev, M., Wang, Y., Chen, J., Dunne, D., Tsangouri, C., Dell, N., Naaman, M., & Estrin, D. (2019). How Intention Informed Recommendations Modulate Choices: A Field Study of Spoken Word Content. In The Web Conference. ACM.
