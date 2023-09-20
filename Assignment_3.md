[Whole website for this project](https://qijiazhoux.github.io/qijia_zhou_portfolio/Assignment_3.html)

## Step one: find a data visualization:

![image](https://github.com/QijiaZhouX/qijia_zhou_portfolio/assets/143776318/b303323b-5347-4fbf-a08d-8c227e3c1445)

<a href="https://projects.flowingdata.com/life-expectancy/" target="_blank">Life Expectancy Data Visualization</a>  

This is an interactive visualization, as seen through the link above. It measures the life expectancy of different countries over the years; each line indicates a nation, and the audience can extract the data point from the visualization by clicking each line. 


## Step 2: Critique

Usefulness: 4 out of 10    
The overall usefulness is low because it is too crowded, and hard to tell them apart; the comparison is not that strong and transparent in terms of the regions they fall into. I like the interactive features that I can click on the visualization, but Ing the need for reformation from the graph is still hard.   
Completeness: 8 out of 10   
The graph has many valuable information and data points, and they did try to include all the data points.  It has a description and some stories behind the data, which is good information.    
Perceotibility: 4 out of 10   
Even though I like the interfaces, it is hard to get any insights from the data besides the global life expectancy is increasing over time; I am not confident whether there will be a lot of takeaways from the visualization, and I got a little frustrated by looking at it for a while.    
Truthfulness: 8 out of 10    
The spacing of the x-axis and y-axis are valid, and they captured the accurate information from the dataset.    
Intuitiveness: 8 out of 10    
I like how the x-axis represents time flow, and iy moves from left to right, and the high and low of the life expectancy is easy to get.   
Aesthetics: 7 out of 10   
I like the colors and think the graph looks good with limited regions highlighted.   
Engagement: 8 out of 10   
I like how the audience can interact and play with the  data points, I find the experience interesting. 

Overall, this visualization looks overwhelming to me. There are so many data points, and getting the information for specific countries or regions worldwide is hard. I like the interaction of the graph and the way that the audience can go through all the countries and see the trends. I like the way that the author wrote there are several data points that we should draw more attention to and connect the history with the life expectancy value. The graph is intuitive, and it is easy for the audience to see the world's life expectancy trends. I also like how we can select the region from the graph and highlight only that data. The problem is that we can not identify the data and get an immediate takeaway. Even though the author chose to include all the data points for every country, comparing them with each other is difficult. To improve, I came up with several solutions. 1. Using the word map and color to show the difference in life expectancy across countries. 2. Plot Lines for specific countries of interest to show the trends. 3. Add additional information like GDP values, and do a dot plot to show the change in life expectancy over the years and compare the difference with countries with different GDPs.   

The primary audience can be anyone curious about global life expectancy and wants to study how certain events or factors like GDP influence life expectancy and how the value changes over time and across different regions. The visualization could be more effective in reaching the audience. Even though there are so many things to take away, it is hard to draw a practical conclusion besides the overall life expectancy increasing over time. However, if the audience is patient enough and has prior knowledge or is willing to gather more information, it is still possible for the audience to get a good takeaway.   

This type of visualization could be more successful. The comparison between countries and regions needs to be included, even though that is something the author intends to do. It is hard to compare all of those data points. Instead of a line chart, a dot chart or a map can be a better approach. Adding more data points in the graph is also better to give the audience additional insights.   

## Step 3: sketch out solutions

<div class="flourish-embed flourish-map" data-src="visualisation/15044305"><script src="https://public.flourish.studio/resources/embed.js"></script></div>  

My primary idea of making this data more accessible for people to understand is using a map. As we can see, the darker region on the map means a place with a higher life expectancy; I also tried to get the population of the nations represented by the circle in the graph (I found it a little distracting, though).  I included only two years of data in the chart. 


![Sketch 1](https://github.com/QijiaZhouX/qijia_zhou_portfolio/assets/143776318/2758a27c-b769-42ad-9e32-0daa06eca44d)

My second idea was to include additional data points to the original dataset; I feel like the life expectancy difference alone is not a good story to tell, and I feel like there might be missing content there, so my idea was to add a separate data set (like GDP), a and add more information to the data. I assume there might be a correlation between the country's GDP and life expectancy, and I would like to find out.

## Step 4: test the solution

Participent 1: Young Adult 20s  
Q: Can you tell me what you think this is? (both graphs) 
A: The first one (map) is clear; I believe this life expectancy for different countries. The only thing I am confused about about about is that the map is missing some regions, such as The US. Is that just super low or is it just missing? I like the overall look of the graph; it is good information, and I like the interaction.   
The second one I need clarification on; it takes a little thinking and can be hard to get. I hope there is more information on the Y axis, and I am confused about about about the dot. But this one can show more details. If the dots mean country, does it mean the higher GDP will result in higher life expectancy?  Etc.   

Participient 2: Student 20s    
Q: Is there anything you would change or do differently? 
A: The color of the dots can be different, and you should take the consideration of color blindness into account. Also, all the dots are together, so it is hard to tell which one is from which year; if there is a separation between the years, it would be better.    
Another thing I am concerned about is the causality and correlation of GDP and life expectancy. I don't know if the audience will think there is a causality relationship between the GDP and life expectancy, and I don't think that will be a correct conclusion.     

Take Aways:    
The two approaches both have their advantages; the first one is more intuitive but has less information, the second one needs more description and better design. 
## Step 5: build solution
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tableau Embed</title>
</head>
<body>

    <div class="tableauPlaceholder" id="viz1695225198086" style="position: relative;">
        <noscript>
            <a href="#">
                <img 
                    alt="World Life Expectancy From 1990 to 2022 for Countries with different GDPIs. Is there a correlation between the GDP value and the life expectancy?" 
                    src="https://public.tableau.com/static/images/Wo/WorldlifeexpectancyandGDP/Sheet3/1_rss.png" 
                    style="border: none"
                />
            </a>
        </noscript>
        <object class="tableauViz" style="display:none;">
            <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
            <param name="embed_code_version" value="3" />
            <param name="site_root" value="" />
            <param name="name" value="WorldlifeexpectancyandGDP/Sheet3" />
            <param name="tabs" value="no" />
            <param name="toolbar" value="yes" />
            <param name="static_image" value="https://public.tableau.com/static/images/Wo/WorldlifeexpectancyandGDP/Sheet3/1.png" />
            <param name="animate_transition" value="yes" />
            <param name="display_static_image" value="yes" />
            <param name="display_spinner" value="yes" />
            <param name="display_overlay" value="yes" />
            <param name="display_count" value="yes" />
            <param name="language" value="zh-CN" />
            <param name="filter" value="publish=yes" />
        </object>
    </div>

    <script type="text/javascript">
        var divElement = document.getElementById('viz1695225198086');
        var vizElement = divElement.getElementsByTagName('object')[0];
        vizElement.style.width = '100%';
        vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
        var scriptElement = document.createElement('script');
        scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
        vizElement.parentNode.insertBefore(scriptElement, vizElement);
    </script>

</body>
</html>


I chose this to be my final solution. With more info about the GDP, I feel this is a better story to tell the audience. I changed the color and made fewer contracts. I also tried to add a description on the top to make it clearer. 
