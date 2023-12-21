# Language of strategic competition: The U.S.-China dynamics reflected in the New York Times from 2009 to 2020
A research project for _Social Media Analysis_
By Ján Cipár, Antonia Pup, Rebeca Olmos del Canto and Defne Ulusoy

## Table of contents
[Introduction](https://github.com/jancipar/US-China-relations/blob/main/README.md#introduction)   
[Literature review](https://github.com/jancipar/US-China-relations/blob/main/README.md#literature-review)   
[Methodology and corpus consolidation](https://github.com/jancipar/US-China-relations/blob/main/README.md#methodology-and-corpus-consolidation)   
* [Search query](https://github.com/jancipar/US-China-relations/blob/main/README.md#search-query)
* [4 key components of the three corpora](https://github.com/jancipar/US-China-relations/blob/main/README.md#4-key-components-of-the-three-corpora)
* [Limitations](https://github.com/jancipar/US-China-relations/blob/main/README.md#limitations)

[Frequencies](https://github.com/jancipar/US-China-relations/blob/main/README.md#frequencies)  
* [Most frequent words](https://github.com/jancipar/US-China-relations/blob/main/README.md#most-frequent-words)
* [Most frequent people](https://github.com/jancipar/US-China-relations/blob/main/README.md#most-frequent-people)

[Topic modeling](https://github.com/jancipar/US-China-relations/blob/main/README.md#topic-modeling)   
* [Analysis of topic modeling by term](https://github.com/jancipar/US-China-relations/blob/main/README.md#analysis-of-topic-modeling-by-term)
* [Limitations](https://github.com/jancipar/US-China-relations/blob/main/README.md#limitations-1)

[Sentiment distribution](https://github.com/jancipar/US-China-relations/blob/main/README.md#sentiment-distribution)
* [Sentiment analysis on the whole corpus](https://github.com/jancipar/US-China-relations/blob/main/README.md#sentiment-analysis-on-the-whole-corpus)
* [Sentiment analysis per year](https://github.com/jancipar/US-China-relations/blob/main/README.md#sentiment-analysis-per-year)

[Bibliography](https://github.com/jancipar/US-China-relations/blob/main/README.md#bibliography)  


## Introduction
Relations between the United States of America (from now on referred as U.S.) and People's Republic of China have caught much international attention during the past decade. Due to the increased importance of the latter and the tensions between the two actors, the topic was a top priority in U.S.'s national security conversation. Some of the thought leaders of the Republican party even called the advent of a New Cold war (Carafano, 2023) between the two geopolitical powers of the moment. Considering the political sciences relavance of the subject, our group has chosen to focus on U.S.-China relations coverage by the New York Times from 2009 to 2020.

The time period of 2009-2020 has been chosen for several reasons: 1) It is large enough to show a pertienent time evolution, but short enough to be covered in detail; 2) it covers three _finished_ presidential terms, allowing for comparison between them; 3) and it covers a recent period, but with enough distance to do so retrospectively.

The New York Times newspaper has been chosen considering its accessibility, but also its consistent adherence to high editorial standards, as evidenced by the numerous Pulitzer Prizes. Moreover, its reputation as a reliable and influential source positions it as a noteworthy contributor to the discourse on global affairs. Its ability to capture a wide range of viewpoints and narratives that have shaped perceptions of the China-U.S. relationship over time. Furthermore, by recognizing The New York Times' center-left editorial stance, we affirm our commitment to acknowledge potential bias, while appreciating the newspaper's unique insights.

In our research, our goal is to provide valuable insights into the reciprocal relationship between media portrayals, particularly from influential sources such as The New York Times, and the dynamic nature of China-U.S. relations. By acknowledging the substantial influence of the newspaper, both within the U.S. and globally, we seek to illuminate its role in shaping public opinion and reflecting prevailing sentiments within society.  

In addition, our aim is to capture the diverse narratives and perspectives that have molded our understanding of this pivotal geopolitical relationship over time. Through this exploration, we strive to contribute insights into how media portrayals, especially from influential sources like The New York Times, have not only mirrored but also influenced the evolving nature of China-U.S. relations. This endeavor offers a valuable lens through which to comprehend the intricate complexities of this vital global partnership. Our approach remains thoughtful and inclusive as we navigate the complexities of this global partnership, recognizing the multifaceted nature of media influence. Through this exploration, we aim to provide a thorough and valuable perspective on the evolving narratives surrounding China-U.S. relations, adding depth and context to our research endeavor.

## Literature review
The great power competition between the US and China is without a doubt one of the most pressing issues of governance today. Even before the 2000s, the economic relations between the two actors have been described as "troubled" (Noland, 1996), and their dynamics was already pivoting as the most complex challenge of the 21st century. Today, in this strategic conversation, the future of liberal internationalism (De Graaff and Van Apeldoorn, 2018) as we know it it's at stake, and the world dynamics are already massively influenced by the emergence of China as a global power and the way US is reacting to this challenge.  

In the aftermath of Barack Obama's inauguration on January 20, 2009, the initial years of his presidential term were characterized by a prevailing positive sentiment in U.S.-China relations. During this period, media portrayals of China generally leaned toward the favorable, reflecting a climate of cooperation and mutual understanding between the two nations. Although the bilateral trade relations had grown in those years, the same period was marked by a trigger in the US policy debate caused by the fact that China refused to adopt a floating currency and failed to implement a series of its obligations as part of the World Trade Organization, especially the ones regarding intellectual propriety rights. Members in the Congress, especially the Republican ones, had urged the Obama administration for tougher stances against China's economic irresponsibility for eliminating the economic policies that were considered to be antagonizing with the interests of U.S. (Morrison, 2008).  

The academic debate has often associated this conundum by distinguishing between a power transition and a hegemonic succession, especially since China is considered to be the most persistent challenge at U.S.' hegemony since the end of the Cold War and the fall of the Soviet Union (Clark, 2011). The "strategic distrust" (Lieberthal and Jisi, 2012) between the two economic challengers appeared in the American national security debate environment long before we have seen actual de-risking direct measures that lead the bilateral relation. For the policy makers in the United States, the growing military investment, the strategic ambiguity in the Asia-Pacific, coupled with lack of transparency and willingness to signal clear foreign policy interests was particular worrisome. Furthermore, the fact that although Chinese economy growth was stellar (about the same time when US experienced significant difficulties to cope after the international financial crisis in 2008), the lack of prospectives for political reform was more difficult to grasp.  

However, a palpable shift in diplomatic dynamics occurred with the transition to the Trump administration. In 2017, the promotion of a new national security strategy brought important amendments to the bilateral vocabulary with China being labeled as a “revisionist power” (Zhao, 2019), and US ready to enter a novel era of strategic competition. The advent of the Trade War and the multifaceted challenges posed by the COVID-19 pandemic introduced a discernible transformation in how China was depicted in the media. This period marked an evolution in U.S.-China relations, portraying a landscape that was not only complex but at times contentious under President Trump's leadership. 2018 was a particular important moment in the relation of the these two world largest economic powers (Itakura, 2020), notably due to the fact that they have imposed harsh import tariffs against the other, which lead to the reduce of a variety of sectoral imports to the U.S. and China. Trade conflicts between U.S. and China had a growing impact on most countries, especially in GDP and manufacturing employment, albeit it benefited their welfare and trade (Li, He and Lin, 2018). This trade war was not limited to import tariffs or economic relations in general, but involved new limits on high-tech products, political competition and a diplomatic polarization with worldwide effects. The protectionist trade approach of the US under Trump presidency has been cited as the "policy of national egoism within the framework of the economic patriotism" (Kapustina et al., 2020), in which the sole economic interests of the American nation Donald Trump aimed to restored were a more important priority than the interests of the partners and the obligations derived from multilateralism. Following the conclusion of Trump's presidency, Joe Biden assumed office with a diplomatic approach that aimed to soften relations with China. 

## Methodology and corpus consolidation
To ensure a comprehensive and accurate representation across each year, we meticulously designed our methodology. Our primary objective was to maintain consistency and equal distribution of articles throughout our selected timeframe. To achieve this, we carefully selected 500 articles for each year, spanning from the inauguration of President Obama on January 20, 2009, to the inauguration of President Biden on January 20, 2021. This approach not only ensures accuracy but also provides a balanced dataset, aiming for an unbiased analysis.

### Search query 
    print(number_of_articles(api_key=my_api_key, keyword='U.S.-China relation'))

Our __search query, "U.S.-China relation"__ was deliberately chosen for several reasons. The New York Times predominantly uses "U.S." to refer to the United States, and given its status as an American newspaper, the term "U.S.-China" specifically denotes bilateral relations between the US and China, always prioritizing the US in its representation. To eliminate articles discussing the US or China in isolation, we intentionally omitted single words such as "US," "China," "Washington," "Beijing", “Obama”, “Biden”, “Jinping” or “Jintao” from our search parameters.

Following the retrieval of articles, we first compiled them into one consolidated file. Additionally, we structured __three distinct corpora__, arranged in the chronological order to facilitate a nuanced analysis:
1. Obama First Term (2009-2013)
2. Obama Second Term (2013-2017)
3. Trump Term (2017-2021)

This segmentation proved crucial as our project revolves around the media portrayal of the U.S.-China relations. By examining variations between Obama's two terms and contrasting the approaches of a Democrat (Obama) and a Republican (Trump), we aimed to discern the impact of changing political landscapes on media depictions. Furthermore, we sought to investigate whether Obama's policy towards China remained consistent throughout his two terms and explore the divergences in approach between a Democrat and a Republican towards China.

During our analysis, we encountered columns in our corpora lacking values, prompting the removal of empty columns. While this step resulted in inconsistencies in the article count across different sections, it was essential for a robust application of topic modeling and sentiment analysis.

Our overarching goals encompass two primary objectives:
- Trace the Evolution of U.S.-China Relations Representation within The New York Times
- Examine Discrepancies Between Media Portrayal and Actual Political Discourse
    - Is media discourse more critical than political discourse?
    - Does media coverage extend beyond political aspects to encompass other dimensions?
    - Does the media predominantly portray China negatively, or are there critiques of the US government as well?

### 4 Key components of the three corpora
To achieve our research objectives, we meticulously scrutinized four key components within each of the three corpora:

1. __Identification of Prominent Figures in Headlines and Lead Paragraphs__: We systematically identified and analyzed individuals mentioned in both headlines and lead paragraphs to gain insights into the key figures driving media narratives.

2. __Topic Modeling for Discerning Dominant Themes Across Time__: Employing advanced topic modeling techniques, we delved into the datasets to uncover prevalent themes evolving over the specified timeline. This facilitated a nuanced understanding of the dynamic shifts in media coverage.

3. __Sentiment Analysis to Assess Media Favorability Toward China in Relation to Diplomatic Developments__: Through sentiment analysis, we gauged the tone and favorability of media coverage concerning U.S.-China relations, aligning our assessment with the corresponding diplomatic events to capture the broader context.

4. __Frequency Analysis of "Trade" and "Security" Over Time__: We systematically tracked the frequency of specific terms, such as "Trade" and "Security," throughout the selected timeframe. This enabled us to quantify and assess the degree of emphasis on these critical aspects and their role in shaping the media's representation of the ongoing rivalry between the two nations.

### Limitations

However, it is essential to acknowledge certain limitations inherent in our approach for a holistic interpretation of the findings. Notably, the following considerations underscore the potential constraints of our project:

- __Media Source Bias__: Relying solely on articles from The New York Times introduces a potential selection bias, limiting the diversity of perspectives from different media sources. This bias may impact the overall representativeness of our analysis, and findings should be interpreted with this limitation in mind.

- __Search Query Specificity__: The use of the search query _"U.S.-China relations"_ might overlook relevant articles using different terminology, potentially excluding nuanced discussions on the topic. This specificity could lead to gaps in our dataset, impacting the comprehensiveness of our study.

- __Temporal and Spatial Constraints__: The selected timeframe (2009-2021) may not capture long-term trends, and events outside this period could influence U.S.-China relations, limiting the project's comprehensive scope. Recognizing this temporal constraint is vital for understanding the context and potential evolution beyond our specified timeframe.

- __Empty Column Elimination__: Removing columns with empty values in corpora might result in data gaps, potentially impacting the reliability of topic modeling and sentiment analysis. The necessity of this step should be considered when interpreting the outcomes of our analytical methods.

- __Sole Focus on Media Representation__: The project's primary focus on media portrayal might not provide a complete understanding of broader factors influencing U.S.-China relations, such as political, economic, and cultural dynamics. This singular focus may limit the study's depth, and users should exercise caution when extrapolating findings to comprehend the entirety of the complex U.S.-China relations landscape.


Within the context of our research, it is essential to illuminate the contours of our study, taking into consideration various factors that both define and limit the scope of our findings.

Firstly, our attempt to retrieve 500 articles per year reveals an irregularity in the distribution of actual articles. This discrepancy can be attributed to two key factors: the study's encompassing two years, from January 20, 2009, to January 20, 2010, which introduces potential disparities, and the necessity to delete columns devoid of values, leading to an uneven distribution of articles. This unevenness poses a challenge to the precision of our study, particularly in evaluating the evolution of the U.S.-China narrative. Despite this limitation, we maintain confidence in the robustness of our overall findings due to the extended timeframe of our analysis.

Secondly, our decision to exclusively rely on articles from The New York Times (NYT) introduces a potential bias, given the NYT's distinct political stance. This singular journalistic perspective may not fully encapsulate the broader spectrum of the American media landscape. However, it's crucial to acknowledge that the NYT is a widely read and influential newspaper in the U.S. Thus, our study, while reflective of a specific viewpoint, offers a representative glimpse into the broader U.S. media landscape.

Finally, our technical limitations must be recognized. We openly acknowledge the existence of these constraints, leading us to forgo corrective measures. Nevertheless, we believe that transparency in acknowledging these limitations contributes to the integrity of our research, allowing readers to interpret our findings with an informed perspective.


Our study, while not immune to constraints, benefits from the comprehensive nature of our temporal analysis and the significance of the selected media source. Readers are encouraged to approach the results with an awareness of these limitations, understanding that they represent inherent challenges within the scope of the research.

## Frequencies
### Most frequent words
    adjectives = [token.text for doc in spacydocs for token in doc if token.pos_ == "ADJ" and token.text.lower() not in STOP_WORDS]
    nouns = [token.text for doc in spacydocs for token in doc if token.pos_ == "NOUN" and token.text.lower() not in STOP_WORDS]

In our analysis, we decided to extract the 10 most frequent adjectives and nouns. We filtered out the common words using spacy library containing common words such as "more" and "other". The two most frequent adjectives are "Chinese" and "American", which is an unsurprising result. We can also find words __"nuclear", "military" and "economic" among the most frequent words__, which suggests that both security and financial aspects play the most crucial role in the U.S.-China relations.   

Suprisingly, the adjective "Korean" is also among the most frequent adjectives which underscores the importance of North and South Korea in US-China relations. This is further proved by the high frequency of Korean leaders´ names in our analysis of the most mentioned people in the articles.

The ten most common nouns include words such as "government", "officials" and "administration". This underscores the __pivotal role of state institutions__ in mutual relations. Even though we found several non-official actors in our NER analysis, both NER analysis and lexical extraction analysis prove the dominance of governments and governmental officials in US-China relations. Words __"trade" and "war" are also among the ten most common nouns__ which is consistent with the main dynamics of US-China relations in the literature.  

> [The code used for this section is available in the document _Lexical extraction.ipynb_](https://github.com/jancipar/US-China-relations/blob/main/Lexical%20extraction.ipynb "Lexical extraction.ipynb")



### Most frequent people
    def extract_persons(text):
        doc = nlp(text)
        persons = [ent.text.lower() for ent in doc.ents if ent.label_ == "PERSON"]
        return persons

In this analysis, we turn our attention to the __five most frequently mentioned individuals by year__ in a corpus of news articles from 2009 to 2021. Leveraging __Named Entity Recognition (NER) techniques__, we identify and quantify the occurrences of these prominent figures, shedding light on the dynamics of media attention. The outcomes of our analysis offer a mix of anticipated findings and unexpected discoveries. 

The analysis shows that __the most mentioned people are the U.S. presidents Barack Obama and Donald Trump__. This expected high frequency of their occurrence in the articles aligns with their pivotal roles in shaping global affairs and commanding considerable public attention. However, the name “Donald Trump” is mentioned much more times than the name “Barack Obama” which may have been caused by the global situation. While the U.S.-China relations during the Obama presidency were mostly cooperative and peaceful, their relations significantly worsened during the Trump presidency. During Trump's presidency, we can observe the onset of the great power competition and U.S.-China relations became a higher-priority topic for the media.

![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_frequency_people.jpg)
_Figure 1: created by us. Most frequently mentionned 5 people per year from 2009 to 2021._  

Their respective U.S. Secretaries of State, Hillary Clinton and Rex Tillerson, also have generally high occurrences in the articles which underscores the critical role that key officials play in shaping and influencing US-China relations. This consistent high profile of Secretaries of State as well as other key officials such as former US Secretary of Defense Robert Gates in the articles signifies their integral contribution to diplomatic endeavors and their high impact on the discourse surrounding the U.S.-China relations. 

Chinese president Xi Jinping is mentioned primarily from the year 2013, when he became president of the People's Republic of China. However, his name is mentioned much less than the names of the US presidents which might have been caused by the bias of the New York Times as the american newspaper. 

However, as the data reveals, key Chinese and US political figures are not the only drivers of US-China relations. We can observe several actors from third countries and non-official actors as well. In 2009, one of the most mentioned names was former US president Richard Nixon. This is connected to the effort of the then US president Barack Obama, who endeavored to strengthen relations with China: a diplomatic initiative reminiscent of the endeavors undertaken by Richard Nixon in the 1970s. The media compared Obama's efforts to Nixon's.

We can see two key people who significantly influenced U.S.-China relations even though they had no political role. One of them is Chen Guangcheng, a civil rights activist persecuted in China, who fled to the US embassy in Beijing. He was a subject of several negotiations between the US and China. The other is Edward Snowden, an American whistleblower, who leaked highly classified information. He fled to Hong Kong where he spent several weeks following his actions.

The data also reveals which countries play a major role in the US-China relations. It is North Korea, India, Japan, Venezuela, Russia (in later years) and Philippines. Their leaders regularly occur among the 5 most mentioned people by year in the corpus.

## Topic modeling
    lda_model = LdaModel(corpus=corpus,
                       id2word=id2word,
                       num_topics=15,
                       passes=20,
                       chunksize=2000)
    from gensim.models.coherencemodel import CoherenceModel
    cm = CoherenceModel(model=lda_model, corpus=corpus, coherence='u_mass')
    cm.get_coherence()

Topic modeling has been realised on both the corpus encompassing all the articles and on each terms' corpus. We have chosen to __create 15 topics__, since it is a number precise enough to have well-defined topics, but small enough to allow analysis. 

> [The lists will all the assigned topics for the three corpuses are available in the document _Topic modeling - tables with identified topics.pdf_](https://github.com/jancipar/US-China-relations/blob/main/Topic%20modelling.pdf "Topic modeling - tables with identified topics.pdf")

![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_topic_modelling_all_corpus.jpg)
_Figure 2: created by us. Topic modelling applied to all articles from 2009 to 2021._


__Several key topics__ appeared in all or most of the topic modellings:
- Russia-related security issues
- Finance and economy, mainly USA's
- Climate change
- Iran and nuclear weapons
- Technology and Huawei
While we cannot exactly see a swift between security to finance topic in between terms, we can see that these two are _the_ main topics of dicussion concerning U.S.-China relations. Finally, some people, as Hillary Clinton and Mike Pompeo, were so mentionned that they could even be categorised as a topic themselves.

### Analysis of topic modeling by term
![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_topic_modelling_Obama_1.jpg)
_Figure 3: created by us. Topic modelling applied to Obama's first term from 2009 to 2013._

In Figure 3, representing the 15 main topic's of __*Obama's first term (2009-2013)*__, we see that there is almost an overalapping between topic related with international relations and politics (numbers 1, 3, 12 and 14 of the graphic). Climate change (number 15) is perhaps the most encompassing topic after U.S.'s economy (number 12). A curious topic, for it is well define and separate from others is that of Iran and nuclear weapons (number 9).

![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_topic_modelling_Obama_2.jpg)
_Figure 4: created by us. Topic modelling applied to Obama's second term from 2013 to 2017._

In Figure 4 representing __*Obama's second term (2013-2017)*__, we see many overlappings at the bottom, with little apparent thematic coherency. Climate change (number 8), besides being more closely related to China, is also quite broad. Perhaps the most interesting topics are those of Russia-related security issues (numbers 5 and 14), since they appear to be linked with Taiwan. We also see the appearence of the first topic exclusively related to finance (number 13).

![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_topic_modelling_Trump.jpg)
_Figure 5: created by us. Topic modelling applied to Trump's term from 2017 to 2021._

Finally, __*Trump's term (2017-2021)*__ is difficult to read, for number 3 greatly disrupts its configuration. This topic seems to be a mix of click-bait articles and White House day-to-day procedures. Climate change's extension (number 10) has been reduced, to the advantage of topic focussing more on domestic matters (number 6 on White House's security policies and number 14 on Biden and the election): this shift perhaps shows an increased importance given to domestic matters by the New York Times, or also a further consideraton of China within U.S.'s politics. Iran and nuclear weapons (number 5) is also present, as well as finance (number 7) and even a distinct topic on North Korea (number 12).

### Limitations
    docs = [[token for token in doc if len(token) > 2] for doc in docs]

Despite getting rid of words with 2 characters, there are still words as 'the', 'our' or 'she'. Hence the existance of topics who do not contribute to the analysis, as topic 15 (14 in the graph) of the overall topic modeling, or topic of X. With more knowledge in coding, some __composed words should have remained as a single token__, to facilitate the analysis: instead of the code understanding 'White' and 'House' as two separate tokens, and the same goes for people's names.


## Sentiment distribution
    model_name = "nlptown/bert-base-multilingual-uncased-sentiment"
    tokenizer = BertTokenizer.from_pretrained(model_name)
    model = BertForSequenceClassification.from_pretrained(model_name)

The sentiment analysis has been done using Bert. Its interest for this analysis is on the fact that it shows the positive, negative or neutral connotations attached to the U.S.-China relations by article. As such, it might help in the understanding of general trends and evolutions through the different presidential terms.

> [The code used to do the sentiment analysis can be found in the document _Sentiment analysis_Bert.ipynb_](https://github.com/jancipar/US-China-relations/blob/main/Sentiment_analysis_Bert.ipynb "Sentiment_analysis_Bert.ipynb")

### Sentiment analysis on the whole corpus
    labels = ['Positive', 'Negative', 'Neutral']
    percentages = [positive_percentage, negative_percentage, neutral_percentage]
    plt.bar(labels, percentages, color=['green', 'red', 'blue'])
    plt.xlabel('Sentiment')
    plt.ylabel('Percentage')
    plt.title('Sentiment Analysis of Articles')
    plt.show()

The first sentiment analysis realised covers the entirety of the corpus, from 2009 to 2020 (see Figure below). It shows that __46,26 % of all articles were negative, 10,9% positive and 42,84 % neutral__. These results came as unsuprising to us: during the covered period, both the tense U.S.-China relation and China's politics have not been presented under a flattening light to the U.S. public. The high percentage of neutral articles may depict the technical character of their relations on some subjects, but also The New York Times' unsensational approach to most topics.

![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_sentiment_analysis_1.jpg)
_Figure 6: created by us. Overall sentiment analysis from 2009 to 2020._

### Sentiment analysis per year
    sentiment_percentages.plot(kind='bar', stacked=True, figsize=(10, 6))
    plt.xlabel('Year')
    plt.ylabel('Percentage')
    plt.title('Sentiment Analysis by Year')
    plt.legend(title='Sentiment', bbox_to_anchor=(1, 1), loc='upper left')

In accordance with the first sentiment analysis, the second and more detailed one shows that the predominance of negative articles over the positive ones can be observed over the whole period 2009-2020. However, we can observe a __significant increase of negative articles from the year 2016__ which coincides with the onset of Trump's presidency. While the proportion of negative articles was around or below 40 % from 2009 to 2015, it was steadily over 40 % from 2016, reaching 66,7 % in 2021. We can also observe a decline in the share of positive and neutral articles. While from 2009 to 2016 the proportion of positive articles was around 12 %, it was mostly below 10 % from 2016. From 2009 to 2016, the share of neutral articles was around 50 %, but there is a stark decline from 2016. The analysis shows that the news coverage was mostly negative, especially since the beginning of Trump's presidency, when relations between the US and China deteriorated significantly.

![Image](https://github.com/jancipar/US-China-relations/blob/main/Image_sentiment_analysis_2.jpg)
_Figure 7: created by us. Sentiment analysis by year from 2009 to 2020._   
 

## Bibliography
Carafano, J. (2023) Winning the New Cold War: A Plan for Countering China | The Heritage Foundation. Available at: https://www.heritage.org/asia/report/winning-the-new-cold-war-plan-countering-china (Accessed: 28 November 2023).  

Clark, I. (2011) ‘China and the United States: a succession of hegemonies?’, International Affairs, 87(1), pp. 13–28. Available at: https://doi.org/10.1111/j.1468-2346.2011.00957.x.  

De Graaff, N. and Van Apeldoorn, B. (2018) ‘US–China relations and the liberal world order: contending elites, colliding visions?’, International Affairs, 94(1), pp. 113–131. Available at: https://doi.org/10.1093/ia/iix232.  

Itakura, K. (2020) ‘Evaluating the Impact of the US–China Trade War’, Asian Economic Policy Review, 15(1), pp. 77–93. Available at: https://doi.org/10.1111/aepr.12286.  

Kapustina, L. et al. (2020) ‘US-China Trade War: Causes and Outcomes’, 73. Available at: https://doi.org/10.1051/shsconf/20207301012.  

Li, C., He, C. and Lin, C. (2018) ‘Economic Impacts of the Possible China–US Trade War’, Emerging Markets Finance and Trade, 54(7), pp. 1557–1577. Available at: https://doi.org/10.1080/1540496X.2018.1446131.  

Lieberthal, K. and Jisi, W. (2012) ‘Addressing U.S.-China Strategic Distrust’, The John L. Thornton China Center at Brookings [Preprint].  

Morrison, W.M. (2008) ‘China-U.S. Trade Issues’. Congressional Research Service.  

Noland, M. (1996) US-China Economic Relations | PIIE. Available at: https://www.piie.com/publications/working-papers/us-china-economic-relations (Accessed: 28 November 2023).  

Zhao, M. (2019) ‘Is a New Cold War Inevitable? Chinese Perspectives on US–China Strategic Competition’, The Chinese Journal of International Politics, 12(3), pp. 371–394. Available at: https://doi.org/10.1093/cjip/poz010.  

Zoellick, R.B. (2013) ‘U.S., China and Thucydides’, The National Interest, (126), pp. 22–30.
