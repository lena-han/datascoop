---
title: "From Colbert to Corden: How Political Guests are Affecting Late-Night Talk Shows"
author: Lena Han
date: 2019-07-24T14:59:50-07:00
featured_image: "/images/LN_background.png"
category: "Politics"
draft: false
---
<sup>*Author: Lena Han*</sup>

Every late-night talk show host seems to have perfected a Trump impression, performing the same signature hand gestures, squinting facial expression, and repetitive speech patterns. And although impressions of political figures are nothing new, the past few years have seen an explosion of political guests, bits, and commentary on late-night talk shows. 

Indeed, the perception that late-night talk shows have become a Trump slugfest has only been heightened by the president himself. In a tweet, he complained that late-night hosts were “unfunny,” “repetitive,” and “always anti-Trump.” However, not all late-night shows are equally political; I sought to identify the most political late-night shows as well as examine the impact of political guests on a show’s popularity. 

**Which Late-Night Hosts are the Most Political?**

To measure how political each late-night show is, I summed the number of political guests invited onto the major talk shows from the past three months. Guests who achieved name recognition primarily due to working directly in politics or contributing political commentary were classified as political.

Most guests could be categorized in a straightforward manner; actors like Aubrey Plaza are not political, politicians like Kamala Harris are political. Although some subjectivity was inevitable, especially for journalists who covered politics in addition to other news, the borderline cases were relatively rare and did not affect enough guests to impact overall conclusions.<sup>1</sup>

Huge variations in how often late-night shows invite political guests are clear. Out of James Corden’s 70 guests throughout the three-month period, not a single guest was remotely political. During that same time period, Stephen Colbert had 26 political guests. The below graph shows the proportion of each late-night show’s guests considered political.

![Proportion of Political Late Night Guests](/images/LN_Political Guest Prop.png)

Unsurprisingly, Trevor Noah has the highest proportion of political guests—*The Daily Show* is known for its political commentary—but Stephen Colbert nearly equals Noah’s numbers. Jimmy Fallon, Jimmy Kimmel, and James Corden’s shows are widely considered more “family-friendly”; their fewer political guests may indicate fears of alienating some of their viewership.

The guests invited to each show are also demonstrative of the backgrounds of the hosts. Colbert hosted a political satire show for many years, so it is fitting that politics have a stronger presence in his show. James Corden comes from an acting and singing background, and most of his guests are similarly entertainers; Conan, a comedian, primarily featured guests with comedic backgrounds.

**TV Ratings Seem Unaffected by Political Guests**

TV ratings are the gold standard of show quality; networks often base show renewals based on TV rating benchmarks. The below scatter plot compares each late-night show’s TV ratings and proportion of political guests.<sup>2</sup>

![Late Night TV Ratings vs Political Guest Proportion](/images/LN_TV Ratings vs Political Prop.png)

Having political guests appears to have no direct effect on a late-night show’s ratings. For late night shows, ratings instead appear much more reliant on network and timeslot. Conan and *The Daily Show*, for instance, are on less popular networks and thus have fewer viewers, lowering ratings. Jimmy Fallon, Jimmy Kimmel, and Stephen Colbert share the best late-night time slot, so their ratings are naturally higher. 

**Alternative Popularity Measurements to TV Ratings**

Although the number of political guests seems to have little impact on TV viewership, other measurements of popularity tell a different story.

Late-night shows are increasingly being watched online via YouTube clips, rather than live on TV. Whereas TV ratings may be a somewhat passive result of favorable time slots, YouTube subscriptions is perhaps a more democratic way of assessing active viewership. 

![Late Night Youtube Subscribers vs Political Guest Proportion](/images/LN_Youtube Subs vs Political Prop.png)

Interestingly, a slight negative correlation between proportion of political guests and YouTube subscribers appears. This trend is reflective of the broader appeal for the signature segments on James Cordon or Jimmy Fallon’s shows; singing karaoke or doing musical impressions with mega pop stars will always be easier to consume than pointed political field pieces on The Daily Show. Although the lowered subscription numbers for more political shows is not directly a result of featuring more political guests, it reveals the more niche audiences such shows attract.

Measuring the favorability ratings of each host corroborates this story. Using results from a March 2019 survey, where respondents ranked shows ranging from “Very Favorable” to “Very Unfavorable,” I created a favorability metric for each show. A score of -100 indicates perfect unfavourability; a score of 100 indicates perfect favorability.<sup>3</sup>

![Late Night Host Favorability vs Political Guest Proportion](/images/LN_Favorability vs Political Prop.png)

A slight negative relationship between favorability and proportion of political guests emerges. Stephen Colbert and Trevor Noah, the two hosts with the most political guests, have the lowest favorability ratings; Jimmy Fallon, Kimmy Kimmel, and James Corden, the three hosts with the fewest political guests, have the highest favorability ratings.

Seth Meyers’s relatively low favorability is due to lack of name recognition, rather than audiences viewing him unfavorably. Consequently, he appears to have the greatest potential to build his popularity; like Trevor Noah, his show focuses on daily news, but he also can appeal to broader audiences. He has yet to strike gold on a signature recurring segment, which is likely key to boosting his popularity.

Notably, although Colbert has a relatively low overall favorability, his TV ratings are still the highest of all the hosts; enough late-night viewers desire political commentary that Colbert is able to maintain high ratings. For late night, audience segmentation seems key; those searching for more political guests can find Colbert on CBS, but those wanting to avoid politics can switch the channel to Fallon on NBC or Kimmel on ABC.

**So does it matter how political a late night show is?**

For now, politics do not seem to matter in late night. TV viewers drive revenue, and as long as ratings are high, it does not matter if a show heavily features political content.

Even though more political content might lower favorability, general favorability has marginal impact on a show’s success. TV shows need not appeal to every person; they simply need to appeal to enough viewers to keep ratings high. For Colbert, the audience is large enough to keep his ratings consistently strong, even if political clips will never go viral the same way Carpool Karaoke might. However, if a fourth late night show were aired during the same time and featured more political commentary, Colbert’s rating would likely take a massive dive because the relatively smaller political audience would be divided. 

On the other hand, if YouTube begins driving revenue for late-night talk shows, that could spell trouble for more political hosts. Even now, networks appear to be adapting to accommodate a greater presence on YouTube. Corden’s viral segments have become integral to his brand, and Lilly Singh is soon to become the first YouTuber to host a late-night show.

Until YouTube’s revenue model become as reliable as television’s though, political late-night hosts need not worry about whether their Trump impressions and presidential candidate interviews are lowering their ratings.

---

<sup>1</sup> The full datasets I used can be found [here](https://github.com/lena-han/datascoop/tree/master/static/datasets/political-late-night). I excluded musical guests because they are not interviewed.
<sup>2</sup> Ratings were the season-to-date ratings at the end of June
<sup>3</sup> The survey results can be found [here](https://www.statista.com/statistics/798845/late-night-show-hosts-favorability-usa/). I assigned point values to each percentage (very favorable=2; somewhat favorable=1; no opinion or never heard of=0; somewhat unfavorable=-1; very unfavorable=-2. The metric I used is the sum of each show’s points divided by two.
