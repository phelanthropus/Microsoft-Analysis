# PHASE ONE PROJECT: Analysis of Movie Performance Over Time

## Introduction
In the realm of entertainment innovation, Microsoft is on the verge of establishing a pioneering movie studio. As the designated analyst for this pivotal initiative, the goal is to decipher the intricate dynamics of successful contemporary films. Armed with comprehensive data encompassing movie titles, revenue metrics, studio affiliations, runtimes, genres, and audience ratings, the analysis aims to distill actionable insights. These findings will serve as a strategic compass, empowering Microsoft's movie studio to produce content that resonates with audiences and maximizes box office success. This exploration is a proactive step towards seamlessly integrating Microsoft into the dynamic realm of original content creation. 
### Explain the real-world problem the project aims to solve.
This project addresses Microsoft's entry into original content creation within the film industry, focusing on establishing a successful movie studio. The real-world problem involves deciphering the key factors contributing to the success of contemporary films. By analyzing data on movie titles, revenue metrics, studio affiliations, runtimes, genres, and audience ratings, the goal is to provide actionable insights. The project aims to empower Microsoft with strategic knowledge, enabling informed decisions and a distinctive presence in the dynamic realm of original content creation. 
### Identify stakeholders and how they would use the project. 
Stakeholders in this project include Microsoft executives, creative teams involved in film production, and marketing teams tasked with promoting the studio's content. Microsoft executives would leverage the project to make informed decisions on the types of films to produce, aligning with market trends. Creative teams would utilize the insights to tailor their film concepts to genres and characteristics that resonate with audiences, increasing the likelihood of success. Marketing teams would benefit by understanding the preferences and trends that drive box office success, allowing them to develop targeted promotional strategies for the studio's films. 
## Data Understanding and Analysis
### Source of Data

The dataset amalgamates information from two primary sources: Box Office Mojo and IMDB.

##### 1. Box Office Mojo:
- Domestic Gross: Contains details on the income generated within the domestic market for various movies.
- Foreign Gross: Encompasses information regarding the income generated in international markets for the same set of movies.
- Studios: Provides insights into the production studios associated with each movie.
##### 2. IMDB:
- Genres: Specifies the genres of the movies within the dataset.
- Average Ratings: Presents the average ratings assigned to the movies.
- Number of Votes: Indicates the count of votes contributing to the calculation of the average rating.

### Description of Data
For the Box Office Mojo dataset, we have the following key columns:
- title: this shows the movie titles
- studio: this shows the studios that have produced the named movie
- domestic gross: this shows the domestic gross income that the studio got from a certain movie. 
- foreign gross: this shows the foreign gross income that the studio got from a certain movie. It refers to the income that the studio got from foreign markets. 
### Data Visualization
#### Top Ten Studios Based on Total Gross
The graph below shows the top ten studios based on total gross. 
![Alt Text](./data%20visualization/output.png)

This is how they can use the data:
- Market Insights: Analyzing top studios' total gross provides crucial market insights, guiding Microsoft in understanding industry dynamics and consumer preferences.
- Success Strategies: Identification of successful strategies in content creation, marketing, and audience engagement equips Microsoft with valuable lessons for their new studio venture.
- Competitive Strategy Formulation: This analysis aids in formulating a competitive strategy, allowing Microsoft to position their new studio effectively in the industry landscape.
- Trend Alignment: Understanding market trends derived from top studios' performance ensures Microsoft aligns their content with current audience preferences.
- Tailored Approach: Armed with insights, Microsoft can tailor their approach, increasing the likelihood of a successful entry into the highly competitive entertainment industry.

#### Top Movies by Total Gross
![Alt Text](./data%20visualization/output2.png)

Microsoft can benefit from this in the following ways: 
- Market Understanding: Analysis of top movies by total gross provides Microsoft with a deep understanding of market trends, enabling informed decision-making for their new studio.
- Content Strategy: Identification of successful elements in top-grossing movies aids Microsoft in crafting a content strategy that resonates with a broad audience.
- Audience Preferences: Insights into the highest-grossing movies reveal audience preferences, helping Microsoft tailor their content to meet and exceed consumer expectations.
- Competitive Edge: Understanding the success factors of top movies allows Microsoft to establish a competitive edge, positioning their studio for success in a competitive industry.
- Strategic Positioning: This analysis assists Microsoft in strategically positioning their new studio by aligning with successful trends observed in top-performing movies.

#### Average Domestic Gross by Studio

![Alt Text](./data%20visualization/output3.png)

Microsoft can use this data in the following way:

- Performance Benchmark: Analyzing the average domestic gross by studio establishes a performance benchmark, aiding Microsoft in setting realistic expectations for their new studio's financial success.

- Identifying Profitable Studios: Recognition of studios with consistently high average domestic gross helps Microsoft identify key players and successful business models within the industry.

- Content Strategy Refinement: Insights into the average domestic gross by studio guide Microsoft in refining their content strategy, focusing on genres and themes that have historically resonated with domestic audiences.

- Market Positioning: Understanding the performance of various studios in the domestic market enables Microsoft to strategically position their new studio for maximum impact and audience reach.

- Competitive Analysis: Comparative analysis of average domestic gross provides Microsoft with a competitive edge, allowing them to tailor their approach based on successful industry precedents.

#### Studios with the most releases

![Alt Text](./data%20visualization/output4.png)

Here are the relevant Insights from the Studio with the Most Releases:

- Market Saturation: The studio with the most releases indicates a high level of market presence, highlighting the potential advantages of a diversified content portfolio for Microsoft's new studio.

- Audience Engagement: A studio with numerous releases suggests a broad approach to audience engagement, providing Microsoft insights into strategies for capturing diverse viewer demographics.

- Content Diversity: The studio's prolific output offers Microsoft valuable insights into the benefits of content diversity, helping them craft a strategy that caters to varied audience preferences.

- Risk Mitigation: Analyzing the studio with the most releases aids Microsoft in understanding potential risks and benefits associated with a high-volume content production strategy.

- Strategic Positioning: Utilizing the lessons from the studio with the most releases, Microsoft can strategically position their new studio to achieve a balance between quantity and quality in their content offerings.

#### Foreign Gross vs Domestic Gross over time

![Alt Text](./data%20visualization/output5.png)

This information can be utilized in the following ways:

- Market Exposure: A pie chart comparing domestic and foreign gross provides a visual representation of market exposure, aiding Microsoft in understanding revenue distribution and potential growth areas.

- International Appeal: Analysis of the foreign gross segment helps identify markets where content resonates strongly, guiding Microsoft in tailoring productions to diverse international audiences.

- Risk Diversification: Understanding the balance between domestic and foreign gross assists Microsoft in risk diversification, ensuring resilience against fluctuations in specific markets.

- Strategic Decision-Making: The pie chart supports strategic decision-making by highlighting the significance of global markets and the potential for revenue diversification beyond domestic boundaries.

- Content Localization: Insights from the chart enable Microsoft to explore content localization strategies, enhancing global appeal and optimizing revenue streams in different regions.

#### Average Rating By Genres

![Alt Text](./data%20visualization/output6.png)

Microsoft can use this data in the following ways: 

- Genre Popularity: Analyzing average ratings by genres helps Microsoft gauge the popularity and reception of different genres, guiding content creation aligned with audience preferences.

- Quality Benchmark: Genres with consistently high average ratings serve as a benchmark for content quality, enabling Microsoft to set high standards for their new studio's productions.

- Audience Expectations: Understanding average ratings by genres provides insights into audience expectations, allowing Microsoft to meet or exceed these expectations in their content offerings.

- Targeted Content Strategy: Insights from genre-specific ratings aid in formulating a targeted content strategy, focusing on genres that have a proven track record of positive audience reception.

- Competitive Edge: Utilizing data on average ratings by genres gives Microsoft a competitive edge, helping them position their studio as a provider of high-quality content across various genres.

#### Scatter Plot of Average Rating vs. Total Gross

![Alt Text](./data%20visualization/output8.png)

This can be used in the following ways:

- Quality-Commercial Balance: A scatter plot comparing average ratings to total gross provides a visual representation of the balance between content quality and commercial success, guiding Microsoft in striking an optimal equilibrium.

- Identifying Blockbusters: Clusters on the plot reveal movies with high ratings and high total gross, helping Microsoft identify potential blockbuster formulas and replicate successful strategies.

- Content Investment: Insights from the scatter plot assist in strategic content investment, allowing Microsoft to allocate resources effectively by prioritizing genres or themes that align with both critical acclaim and financial success.

- Audience Preferences: Patterns in the scatter plot indicate audience preferences, aiding Microsoft in tailoring their content to meet the demands of a discerning and revenue-driven audience.

- Competitive Positioning: Utilizing the plot, Microsoft can strategically position their studio as one that consistently delivers high-quality content with substantial commercial appeal.



## Conclusion
Here is the summary of the key recommendations:
1. Global Appeal Strategy: Given that the foreign market significantly contributes to studios' gross income, Microsoft should prioritize producing films with universal appeal to maximize global success.
2. Genre-Driven Content Strategy: Considering the consistently high ratings of Biographies in recent years, Microsoft should strategically factor in genre preferences when selecting films for production, aligning content choices with audience preferences.
3. Strategic Use of Average Ratings: Rather than relying solely on average movie ratings and gross income indicators, Microsoft should leverage average ratings to discern consumer preferences by genre. This approach ensures a more consumer-centric content strategy, focusing on genres that resonate with viewers.
4. Directorial Talent Acquisition: To enhance their filmmaking team, Microsoft could explore hiring directors based on the genre preferences highlighted in the top grossing films' directorial table. This targeted approach aligns with the observed success of directors in specific genres over the specified time period.