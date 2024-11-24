| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards

### Getting started
I'll start with an introduction to Boston's urban history, cultural background, and local flavor. The city of Boston attracts different types of tourists, and the Airbnb marketplace is not only a part of city life, but also a key for tourists to choose accommodations and for hosts to develop strategies. The question is then introduced: “Which areas are more popular for Airbnb listings? Is there a correlation between price and number of rooms? “These questions form the core of my entire story, and by exploring the patterns behind them, I hope to provide insights that are meaningful to both travelers and hosts.

### Boston Airbnb market overview
At the beginning of my story, I give the audience an engaging opening - I show a map of Boston, marking areas of high density of listings by scattering dots, as well as marking listings at different prices by different colors, e.g., under $250 a night in blue, above in orange. Here I will use a textual narrative to describe why there is a concentration of listings in these areas, as well as analyze possible reasons, including the distribution of attractions, access to transportation, etc.

<div class='tableauPlaceholder' id='viz1732423059802' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Boston Airbnb Overview by Price, Room Type, and Neighborhood' src='https://public.tableau.com/static/images/Ma/MapOverview_17323167102140/Sheet1/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='MapOverview_17323167102140/Sheet1' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/Ma/MapOverview_17323167102140/Sheet1/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='zh-CN' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1732423059802');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Distribution of Airbnb room types in Boston
The map allows you to visualize the distribution of listing types in each area of Boston. For example, the main types of listings in Boston are Entire home/apt and Private room, which are concentrated in areas such as Back Bay, Bright and Downtown. In contrast, Fenway and Charlestown have fewer listings but still attract specific types of tourists.

By analyzing the characteristics of the listings, it can be concluded that tourists generally prefer accommodation with private space, while for hotels and share rooms are not popular in Boston. For hosts, it is possible to adjust the price and estimate the occupancy rate according to the choice of different housing types.

<div class='tableauPlaceholder' id='viz1732423914373' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Airbnb Room Type Distribution' src='https://public.tableau.com/static/images/te/test2_17324237366850/Sheet2/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='test2_17324237366850/Sheet2' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/te/test2_17324237366850/Sheet2/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='zh-CN' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1732423914373');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


### Relationship between number of rooms, region and prices
Further explore the relationship between number of rooms, region and price. The number of listings in different areas directly affects the competitiveness of prices. For example, Back Bay has a high number of listings but higher prices overall, while Fenway has a lower number of listings and a more concentrated price range. And the box plot can reflect the statistical values of price, such as the minimum, median and maximum values in different areas, so as to quickly understand the distribution of price in different areas. It also shows the differences between different groups, for example, Longwood Medical Area is generally more expensive and has fewer rooms, while the outliers (especially high prices) in downtown are hotels.

<div class='tableauPlaceholder' id='viz1732424343519' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='The Secret Behind Prices, Room Type and Regions Revealed' src='https://public.tableau.com/static/images/pr/priceroomtyperegion/Sheet3/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='priceroomtyperegion/Sheet3' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/pr/priceroomtyperegion/Sheet3/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='zh-CN' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1732424343519');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


### Partial Dependence Plot
The PD plot plots the average impact on Airbnb price for each feature, for example, as latitude changes, the change in price is smaller, which means that north and south of Boston have a more limited impact on the price, and looking at the map you can see that those are the suburbs of Boston.

![Latitude Image](https://raw.githubusercontent.com/Ray1208xxxx/Ray-Zeng-Portfolio/main/latitde.png)

Focusing on Minimum Nights, you can see from the map that when the minimum number of days of occupancy increases, the price drops rapidly and eventually levels off, which is consistent with my common sense that short-term rentals tend to be more expensive but longer-term rentals have a price discount, or perhaps tenants generally don't have the need to rent for as long a period of time, so a long period of time with a minimum occupancy requirement is less appealing to the tenant resulting in a drop in the price.

![Night Image](https://raw.githubusercontent.com/Ray1208xxxx/Ray-Zeng-Portfolio/main/night.png)

The main purpose of these partial dependency graphs is to help understand how individual features affect the predicted price, as well as to reveal how the model adjusts the predicted price when specific features change. These plots allow for a better understanding of which factors have the greatest impact on the pricing of Airbnb listings, as well as the specific direction and magnitude of the impact of these factors. More can be found in my [Jupyter Notebook: Airbnb Analysis](https://github.com/Ray1208xxxx/Ray-Zeng-Portfolio/blob/main/airbnb.ipynb).

### Business insights and conclusions: regional pricing and listing strategies

Advice for Travelers:
The visual analysis above shows that Back Bay and Downtown are worthwhile areas to choose if on a budget to experience Boston's core urban living area. If value for money is important, you can choose Bright or Roxbury, which are some distance away from the attractions but cheaper.

Advice to host:
Differentiate pricing strategies by having different listings in different areas, such as optimizing listing amenities and services in areas with dense listings to improve ratings and occupancy. In areas with fewer listings, prices can be adjusted to take advantage of scarcity to attract specific groups of tourists.

A comprehensive analysis of listing prices, number of rooms, and types of listings reveals that the Airbnb market in Boston is full of diversity and opportunities.

# User research 

## Target audience
I want to explore Airbnb pricing through my project, so my primary audience target is users who use Airbnb like me, and secondly my project will potentially help Airbnb hosts as well as city administrators, so they are also my target audience. All three of my target groups have different needs regarding the dynamics and trends of the Airbnb market, for example, users or renters want to find quality and cost-effective accommodation, hosts want to understand how to develop better pricing strategies for their properties and optimize their room amenities to cater to the market, and city managers want to understand the spatial distribution of properties and their impact on the city.

Since renters and hosts are easier to find but city managers are more difficult to interview, I've tried emailing a few but haven't heard back yet, so for now there are only two renters and one host. More specifically, the first renter is a student who has used Airbnb before and is relatively sensitive to price as well as location, the other renter is a freelancer with financial income and traveling habits, while the host is an employee of the company who has rented out homes as a landlord and is familiar with Airbnb data.

## Interview script

Before starting I would briefly introduce the purpose of the study to them and guide them through each chart one by one according to the objectives and ask relevant questions. Then record their ideas and suggestions.


| Goal | Questions to Ask |
|------|------------------|
| **Evaluate whether the visualization clearly communicates key information** | What is your first impression of these charts? Does it quickly capture the key information? |
| **Evaluate whether the presentation effectively communicates the story** | Was there a part of the presentation that stood out to you? Why? |
| **Feedback on overall design and experience** | Do you have any other suggestions for the overall design and experience? |

## Interview findings

| Questions               | Interview 1 (College student, 24 years old, used Airbnb) | Interview 2 (Freelancer, 27 years old, with financial income and traveling habits) | Interview 3 (Company employee, 29 years old, Airbnb host) |
|-------------------------|--------------------------------|-------------|-------------|
| What is your first impression of these charts? | I think it's intuitively designed through the map to clearly show price range divisions, and I can see at a glance in which areas the listings are spread out the most. | The design of the charts is very clear, the color scheme is attractive, and the overall style makes me feel comfortable without being too serious. | The overall layout and design of the charts is very professional, especially the price box charts and the PD charts are very useful for me to be able to quickly find the information I need, such as the statistics of the price in each area and the relationship with other features. |
| Does it quickly capture the key information? (From 0 to 10, 0 is not at all, 10 is perfect) | I would say 7, Mostly ok but it would have been nice to have the backstory. | 8, The map's key information is easy to capture, but the box diagram is more complex and has too much information. | Yes, 7 to 8, I think the presentation would have been more helpful if some of the particular outliers (e.g. high priced listings) had been explained in more detail. |
| Was there a part of the presentation that stood out to you? Why? | I liked how you used the analysis of the concentration of high priced listings in certain high end areas in your presentation, it allowed me to understand the logic behind the data. | I think the whole thing is amazing. | What struck me most was your combination of listing distribution vs. price, which made me think of my own airbnb rental area and pricing strategy. |
| Do you have any other suggestions for the overall design and experience? | I think a backstory could be added to give more information about Boston zoning, etc. | The visualization of the room type can be modified, the map obscures some of the information. | Simplification of the box plot, as well as adding more explanation to the PD plot. |


# Identified changes for Part III

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Add more background information | Adding more information about Boston allows viewers to get a quick overview of Boston as well as helps them understand the visualization. |
| Enhanced clarity of maps | I'll change the map background so that the map no longer obscures important information. |
| Improve the structure of box plots | Use a clearer structure to present the visualization, as well as explain exactly what the median, quartiles, and outliers mean. At the same time, the outliers are marked with more conspicuous colors to highlight the characteristics of high-priced listings. |
| Increased PD Chart Interpretation | Interpret PD charts in more detail to reveal the meaning behind the data. |

Use shorthand as well as tableau for whole story presentations, link can be find in: [this Shorthand page](https://preview.shorthand.com/bhAhzRXfTRzlI3jW).

