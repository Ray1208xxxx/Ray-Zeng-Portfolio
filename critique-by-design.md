| [home page](https://ray1208xxxx.github.io/Ray-Zeng-Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# This is for 
Assignment: Assignment 3 & 4: Critique by Design with Tableau (MakeoverMonday)

# Step one: choose a data visualization from MakeoverMonday
Name: The cheapest countries to study in Europe in 2024

Link: https://www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe

![Cheapest Countries to Study in Europe](https://github.com/Ray1208xxxx/Ray-Zeng-Portfolio/blob/main/cheapest-countries-to-study-in-Europe.png)

> I chose to include this visualization because it was in the first few MakeoverMonday's and I didn't find data on education spending in the US (just kidding). I lived in Australia before coming to the U.S., so I was curious about how much it would cost to live and study in another country. This map of study costs in Europe uses a straightforward, simple approach to show how cost data can be expressed and help users understand the economic impact of different study options. Visualizations like this are an inspiration and example for people like me who have a keen interest in education, data-driven decision-making, and how to make data more accessible.

# Step three: sketch out a solution
<div class='tableauPlaceholder' id='viz1731192470572' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Comparing Annual Study Costs Across Europe (£) The visualization highlights the total yearly cost of studying in selected European countries, combining both tuition fees and estimated living expenses.' src='https://public.tableau.com/static/images/a3/a34/Sheet1/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display: none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='a34/Sheet1' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/a3/a34/Sheet1/1.png' />
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
  var divElement = document.getElementById('viz1731192470572');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


> Firstly for those unfamiliar with the map of Europe they are less able to quickly identify which countries have higher or lower costs to study abroad as the labels only appear when the mouse is hovered over the area, so I added labels for each country and set them to highlight in a contrasting orange color.
>
> Secondly, although the color gradient is able to show how high or low the relative cost is, it does not provide a direct numerical label. This may interfere with accurate comparisons between different countries, and it is difficult for me to compare the high and low costs of different countries by subtle differences in color and lows it doesn't provide a direct numerical label. This could interfere with accurate comparisons between countries, so I added numbers to allow viewers to visually compare number sizes rather than color shades for similarly colored areas.

# Step four: Test the solution
### Feedback Questions:
* Can you tell me what you think this is?
* Can you describe to me what this is telling you?
* Is there anything you find surprising or confusing?

### Feedback
> My roommate, student, mid 20's
> * Can you tell me what you think this is? This looks like a map of Europe showing the annual costs of studying in different countries, including tuition fees and living costs.
> * Can you describe to me what this is telling you? He mentions that the color gradient seems to emphasize that studying in certain countries is more expensive than others. For example, Ireland and the Netherlands look very expensive compared to Romania or Hungary. The color gradient helps to visually differentiate the range of costs in each country.
> * Is there anything you find surprising or confusing? He found the scale on the right a little confusing. It took him a little while to figure out how to match the colors to the values. Maybe a legend or more labels directly on the map would make it more readable at a glance.

> My friend, student, mid 20's
> * Can you tell me what you think this is? This is a data visualization showing the annual cost of study, including tuition fees and estimated living costs, for students in various European countries
> * Can you describe to me what this is telling you? This map tells him that the cost of studying in Western and Northern Europe is higher than in the intermediate regions. By changing shades of color, he can quickly see which countries are more expensive to study in. Overall, this visualization was intuitive and allowed him to quickly understand the financial burden of studying in different countries in Europe.
> * Is there anything you find surprising or confusing? He said he wanted to find the most expensive countries, but it was a bit of a struggle. Asked if I could rank the countries or label them on the map. It would make it easier to see which countries are the most expensive.

# Step five: Build your solution
<div class='tableauPlaceholder' id='viz1731208405169' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='Dashboard 1 ' src='https://public.tableau.com/static/images/a3/a34improve/Dashboard1/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='a34improve/Dashboard1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/a3/a34improve/Dashboard1/1.png' />
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
    var divElement = document.getElementById('viz1731208405169');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if (divElement.offsetWidth > 800) {
        vizElement.style.width = '1000px';
        vizElement.style.height = '827px';
    } else if (divElement.offsetWidth > 500) {
        vizElement.style.width = '1000px';
        vizElement.style.height = '827px';
    } else {
        vizElement.style.width = '100%';
        vizElement.style.height = '727px';
    }
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

> To solve the problem of the label on the right side not being coordinated, I first prepared and converted the data, I created a field with a green icon (i.e. a measure), and used Create Calculated Field to create the Cost Range field, which converts string values with currency symbols and commas to integers:
```
INT(REPLACE(REPLACE([Total yearly living costs and fees], “£”, “”), “,”, “”))
```
I then created a new worksheet, placing the SUM(Cost Range field in the row to be used as a side legend. Finally the newly created worksheet is added to the main dashboard as a side panel.


<div class='tableauPlaceholder' id='viz1731210314546' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='European Countries Ranked by Total Yearly Study Costs: Denmark Tops the List £34,190, Croatia at the Bottom £7,920' src='https://public.tableau.com/static/images/a3/a34version2/Sheet1/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='a34version2/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/a3/a34version2/Sheet1/1.png' />
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
    var divElement = document.getElementById('viz1731210314546');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

> In my friend's feedback, he mentioned that he wanted to find the most expensive countries, but had some difficulty. He asked if it would be possible to rank the countries or label them on a map so it would be easier to see which countries were the most expensive. To address this need, I created a bar chart to aid in the map visualization, making it clearer for users to view and compare the annual study cost rankings of countries. The bar chart shows countries sorted by “Total yearly living costs and fees”, from Denmark, the most expensive, to Croatia, the cheapest.
