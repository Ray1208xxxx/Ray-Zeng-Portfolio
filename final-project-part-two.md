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

# User research 

## Target audience
I want to explore Airbnb pricing through my project, so my primary audience target is users who use Airbnb like me, and secondly my project will potentially help Airbnb hosts as well as city administrators, so they are also my target audience. All three of my target groups have different needs regarding the dynamics and trends of the Airbnb market, for example, users or renters want to find quality and cost-effective accommodation, hosts want to understand how to develop better pricing strategies for their properties and optimize their room amenities to cater to the market, and city managers want to understand the spatial distribution of properties and their impact on the city.

Since renters and hosts are easier to find but **city managers are more difficult to interview, I've tried emailing a few but haven't heard back yet, so for now there are only two renters and one host. More specifically, both renters are students who have used Airbnb before and are relatively sensitive to price as well as location, while the host owns an Airbnb listing in boston.

## Interview script
> List the goals from your research, and the questions you intend to ask. 

Text here!

| Goal | Questions to Ask |
|------|------------------|
|      |                  |
|      |                  |
|      |                  |


Text here!

## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1 (briefly describe) | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| Question you asked here | Insightful feedback            |             |             |
|                         |                                |             |             |
|                         |                                |             |             |


# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

Text here!

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Findings or observations from interviews | Describe what, if any changes you anticipate making to address the observation. |
|                                          |                                                                                 |
|                                          |                                                                                 |
|                                          |                                                                                 |
| ...add more rows as necessary            |                                                                                 |

> ...include any final thoughts you have here. 

Text here!

# Moodboards / personas
> If you did this optional part, include details here.  Otherwise remove this section

Text here!

