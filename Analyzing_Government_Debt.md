# Overview 
The objective of this assignment is to analyze the government debt-to-GDP ratio across countries worldwide. To provide a definition, the government debt-to-GDP ratio is a metric that aids in comprehending the magnitude of a country's debt in relation to its overall economic output. The dataset utilized for this analysis was sourced from the Organisation for Economic Co-operation and Development (OECD).

# Part 1 (Bar Chart)

This figure displays the latest data on the government debt-to-GDP ratio for the year 2022 across various countries. The information is arranged, with the country with the lowest ratio listed first, followed by the country with the highest ratio.

<iframe src="https://data.oecd.org/chart/7kkn" width="760" height="570" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">OECD Chart: General government debt, Total, % of GDP, Annual, latest</iframe>

# Part 2 (Heat Map)
Leveraging the identical dataset, I created a heatmap visualization. This visualization allows for the identification of critical years in each country, pinpointing instances where the government debt-to-GDP ratio experienced significant increases

<div class='tableauPlaceholder' id='viz1706586613403' style='position: relative'><noscript><a href='#'><img alt='Sheet 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Visualizing_Government_Debt3&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Visualizing_Government_Debt3&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Visualizing_Government_Debt3&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706586613403');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# Part 3 (Line Chart)

For this third visualization, I utilized a subset of the data to create a visualization highlighting the government debt-to-GDP ratio of the United States. The focus is on the 5-year period both preceding and following the crucial year of 2008, which marked the beginning of the financial crisis.

<div class='tableauPlaceholder' id='viz1706586975050' style='position: relative'><noscript><a href='#'><img alt='US Government Debt-GDP Ratio: Impact of the 2008 Financial Crisis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Visualizing_Government_Debt2&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Visualizing_Government_Debt2&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Visualizing_Government_Debt2&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706586975050');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# Written Summary

The initial visualization displays the General Government Debt as a percentage of GDP in 2022. Employing a bar chart, the countries are arranged from the lowest to the highest debt, highlighting the comparative levels effectively. Despite the categorical nature of the x-axis data (countries), a single color is utilized, simplifying the representation to focus on classifying countries based on their debt magnitude.

In contrast, the second visualization adopts a heat map format to illustrate government debt across different years. The color scheme employs shades of orange and blue to denote varying debt intensities. Blue signifies years with lower debt, while shades of orange represent periods with higher debt levels, creating a visual contrast for easy interpretation. This dynamic representation enhances the viewer's ability to discern temporal patterns in government debt across countries, offering a comprehensive perspective on the data.

For my visualization, I chose to depict the US government's financial situation five years before and after the 2008 financial crisis. The aim was to illustrate how the crisis impacted government debt. As evident, prior to the crisis, the US government debt was relatively low, but it began to rise after the crisis. This can be attributed to a decline in GDP, coupled with an increase in government spending.
