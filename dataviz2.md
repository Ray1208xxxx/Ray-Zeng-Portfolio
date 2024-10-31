# This is for 
Assignment: Visualizing government debt using Tableau


# My tableau
### Government debt bar chart
![General Government Debt Visualization](https://github.com/Ray1208xxxx/Ray-Zeng-Portfolio/raw/main/export-2024-10-31T13_34_13.992Z.png)

### Heat map
<div class='tableauPlaceholder' id='viz1730341423953' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='General government debt from 1995 to 2019' src='https://public.tableau.com/static/images/A2/A2_17303414121200/Sheet1/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='A2_17303414121200/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/A2/A2_17303414121200/Sheet1/1.png' />
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
    var divElement = document.getElementById('viz1730341423953');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Click the link below to view the interactive Tableau visualization: https://public.tableau.com/views/A2_17303414121200/Sheet1

### Treemap
<div class='tableauPlaceholder' id='viz1730342434616' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='General government debt from 1995 to 2019' src='https://public.tableau.com/static/images/A2/A2Graph2/Sheet1/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='A2Graph2/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/A2/A2Graph2/Sheet1/1.png' />
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
    var divElement = document.getElementById('viz1730342434616');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

### Discuss
I think the heap map is too cumbersome because there is a lot of data and displaying it by year is too cumbersome and I got tired of looking at it, so I wanted to simplify the whole chart to one that I could see the meaning of at a glance.

I came up with the idea of a treemap, which visualizes the overall debt of each country in a more intuitive way, and I can see the relative comparisons between different countries directly. So I removed TIME and only show the total debt for each country from 1995 to 2019. And I changed the color from orange-blue diverging to green-red diverging, and set the median value to 2000, so that I can show that countries below 2000 have less debt, so it is green, and countries above 2000 have more debt, so it is red. Overall, the heat map provides a more detailed view of the debt level of each country for each year, while the treemap provides a visual representation of the overall debt level of each country.


