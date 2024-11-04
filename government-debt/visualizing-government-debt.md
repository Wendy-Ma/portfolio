# Part 1: Working with web-based visualization tools and data
![government-debt-bar-chart](/government-debt/government-debt.png)


# Part 2: Working with Tableau

<div class="tableauPlaceholder" id="viz1730689770739" style="position: relative;">
    <noscript>
        <a href="#">
            <img alt="General government debt% of GDP" src="https://public.tableau.com/static/images/go/government-debt/government-debt/1_rss.png" style="border: none;" />
        </a>
    </noscript>
    <object class="tableauViz" style="display: none;">
        <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
        <param name="embed_code_version" value="3" />
        <param name="site_root" value="" />
        <param name="name" value="government-debt/government-debt" />
        <param name="tabs" value="no" />
        <param name="toolbar" value="yes" />
        <param name="static_image" value="https://public.tableau.com/static/images/go/government-debt/government-debt/1.png" />
        <param name="animate_transition" value="yes" />
        <param name="display_static_image" value="yes" />
        <param name="display_spinner" value="yes" />
        <param name="display_overlay" value="yes" />
        <param name="display_count" value="yes" />
        <param name="language" value="en-US" />
    </object>
</div>

<script type="text/javascript">
    var divElement = document.getElementById("viz1730689770739");
    var vizElement = divElement.getElementsByTagName("object")[0];
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
    var scriptElement = document.createElement("script");
    scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


# Part 3: Create your own visualization

<div class="tableauPlaceholder" id="viz1730697715200" style="position: relative;">
    <noscript>
        <a href="#">
            <img alt="General government debt (1995-2019)% of GDP" src="https://public.tableau.com/static/images/9X/9X7QSC6Q2/1_rss.png" style="border: none;" />
        </a>
    </noscript>
    <object class="tableauViz" style="display: none;">
        <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
        <param name="embed_code_version" value="3" />
        <param name="path" value="shared/9X7QSC6Q2" />
        <param name="toolbar" value="yes" />
        <param name="static_image" value="https://public.tableau.com/static/images/9X/9X7QSC6Q2/1.png" />
        <param name="animate_transition" value="yes" />
        <param name="display_static_image" value="yes" />
        <param name="display_spinner" value="yes" />
        <param name="display_overlay" value="yes" />
        <param name="display_count" value="yes" />
        <param name="language" value="en-US" />
        <param name="filter" value="publish=yes" />
    </object>
</div>

<script type="text/javascript">
    var divElement = document.getElementById("viz1730697715200");
    var vizElement = divElement.getElementsByTagName("object")[0];
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
    var scriptElement = document.createElement("script");
    scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

According to the map plot, I found that the countries in North America (Canada, USA, Mexico) have ratio under 100 from 2004-2009 and then have ratio larger than 100 after 2009. Japan has a gradually increasing trend from 1995 to 2019.
I still used orange and blue divergence color because I think it is clearer to see the comparison. And two colors could seperate the regions which didn't have any datapoint. I added the data label to ensure users could see the exact value of the ratio. I also added the filter to ensure the users could see the data in different years.
The pros of bar chart are that it is easy to read and compare the data in one specific year. The cons are that it is hard to compare the data in different years.
The pros of highlight table are that we could see every datapoint in one table and could compare the data in different years by strong constrast of colors. Also we could have a direct sense of which data point is missing. The cons is that there are too many data points in one table so it is hard to show all of them to the audience. If we need to present them in a slide like we usually need to do in the workplace, it is impossible to paste the full picture into the slide.
The pros of map plot are that we could see the geographical representation of location directly and compare the values. As for me, it is hard for me to match the country/region code to the country itself so a map plot is more intuitive for me. And it is easier to get insights about geographical trend, like the trend of North America from 2004-2009. The cons are that the plot couldn't depict the data in different years and it will be hard to look at some small countries if the users couldn't zoom in,