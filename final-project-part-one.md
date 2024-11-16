| [home page](https://ray1208xxxx.github.io/Ray-Zeng-Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Project Name: Explore popular tourist lodging locations in different areas of Boston using Airbnb Listings Data

## Summary of the project
My project will use data from Inside Airbnb to explore the distribution of Airbnb listings in Boston and their price trends. The visual analysis of Airbnb listings will reveal which areas of Boston are most preferred by travelers and which factors affect the price of listings, such as the type of listing, location, amenities, and reviews.

In this project I plan to use Python for data processing and data analysis, I want to make a project with machine learning code and visualization for job interviews, I will use Python to analyze different types of listings such as clustering using the KMeans algorithm to find similar types of listings and potential market segments. In addition, I plan to use Partial Dependence plots to show the marginal effect of features on the model's predicted results, helping to provide insight into the impact of individual features on the performance of listings.

The goal of this project is to provide users with a better understanding of the Airbnb market within the city of Boston, thus providing useful insights for hosts, travelers, and decision makers.

## Project Structure
### Setup: Introduce the background
I would start this project using my story that I am getting ready to plan a trip to Boston and would like to know the number of listings and prices in different areas. I would then use a panoramic map to show the distribution of Airbnb listings within the city. By using markers with different densities, the viewer can get a quick idea of which areas have a higher concentration of listings.

### Conflict: Exploration and Problem Presentation
Next, I will explore in depth the main factors that influence the price of Airbnb listings in Boston, such as location, listing type, amenities, and user reviews. I will then use cluster analysis KMeans to identify differences in listing types, and a price heat map to show significant differences in prices across regions. The goal of the conflict section is to reveal the challenges faced by landlords and tenants when pricing and choosing listings, especially in terms of how to balance the choice between price and location.

### Rising Action: Analyze and Discover 
Further analyze the impact of each listing type on rental performance, including the relationship between the number of reviews and booking rates. Demonstrate trends in the impact of certain characteristics on the price or performance of listings through the use of partial dependency graphs to better understand the impact of these characteristics on the market. Here I want to show what specific steps landlords can take to improve the attractiveness of their listings, which will increase booking rates and revenue.

### Resolution: Conclusions and Recommendations
Finally, I will summarize the key findings and provide some practical advice for both landlords and tenants. For example, for landlords, how specific amenities can be utilized to enhance competitiveness and for tenants, how to find value for money accommodation. With these recommendations, I hope to provide targeted strategies for different user groups to help them make better decisions in the market.

## Initial sketches
### Overview Map & Category Heatmap
![Map Visualization](https://github.com/Ray1208xxxx/Ray-Zeng-Portfolio/blob/main/Map.jpeg)
> Overview map is to help the audience quickly understand the spatial distribution of Airbnb listings across Boston, with colors ranging from blue to red representing low to high prices, highlighting the differences in pricing across neighborhoods.
> Category Heatmap highlights different listing types and their market positioning, red for Airbnb Hosts can list entire houses/apartments and green for private rooms. The polyglot can help hosts understand which category their listing belongs to and what features make it stand out.

### Partial Dependence Plot
![Price Distribution](https://github.com/Ray1208xxxx/Ray-Zeng-Portfolio/blob/main/PD.jpeg)
> This plot provides a partial dependence showing the marginal effect of a particular feature. Help Airbnb Hosts understand how certain characteristics (e.g., number of room, user ratings, etc.) affect the price of their listings so they can take targeted optimization measures.


## Data Sources
| Name                 | URL                                                                                 | Description                                                                                             |
|----------------------|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| **Primary Data Source**  | [link](https://data.insideairbnb.com/united-states/ma/boston/2024-06-22/visualisations/listings.csv)  | Summary information and metrics for Boston listings through June 2024, including listing location, listing type, price, amenities, number of reviews and ratings. |
| **Explore this dataset** | [link](https://insideairbnb.com/boston/)                                         | Some visualization and background information on the basis of the dataset.                             |
| **GeoJSON data file**    | [link](https://data.insideairbnb.com/united-states/ma/boston/2024-06-22/visualisations/neighbourhoods.geojson) | GeoJSON file of neighbourhoods of the city.                                                            |

**How to use data:**
 - **Distribution of listings:** Using geographic location data, a panoramic map is drawn to show areas where listings are concentrated and sparse.
 - **Price analysis:** Use price data combined with geographic information to generate a price heat map to show price differences and areas of high and low prices.
 - **Influencing factor analysis:** Explore the main factors influencing the price of a listing by combining information such as the listing's facilities and reviews.
 - **Relationship between reviews and booking rate:** Using review data, analyze how hosts' reviews affect the popularity of listings.


## Method and medium
Tools and Applications:

| Tool                     | Purpose                                                                                    |
|--------------------------|--------------------------------------------------------------------------------------------|
| **Python**               | Data cleaning, Feature engineering, Preliminary data exploration, Cluster analysis         |
| **Tableau**              | Data visualization                                                                         |
| **Shorthand (maybe use)**| Data storytelling and combining charts and text to create a more engaging experience       |

The final data will be processed and imported into Tableau for visualization, presenting the distribution of listings, price differences, the influence of hosts, popular areas, etc., to tell a story about the Airbnb marketplace. Through these visualizations, my project is able to reveal the geographic concentration of Airbnb listings in Boston, analyze the main factors affecting prices, and explore the relationship between reviews and booking rates.
