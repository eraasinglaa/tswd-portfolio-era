| [home page](https://eraasinglaa.github.io/tswd-portfolio-era/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Global Government Debt Analysis: Insights from OECD Data

This portfolio page presents an analysis of government debt-to-GDP ratios across various countries, using data from the Organization for Economic Co-operation and Development (OECD). Through interactive and static visualizations, we explore trends in government debt levels, comparing the fiscal policies of different nations and highlighting their responses to significant economic events.

The analysis is divided into three parts, each utilizing different visualization techniques and tools to draw insights from the OECD dataset:

1. **Part 1: Web-Based Visualization and Data Exploration**  
   Using the OECD’s online data visualization tools, we explore government debt levels for selected countries in a recent year, creating an interactive bar chart. This chart provides a snapshot of debt-to-GDP ratios across countries, helping to understand which nations carry high or low debt levels relative to their economic output.

2. **Part 2: Highlight Table (Heatmap) in Tableau**  
   A heatmap created in Tableau allows for an in-depth comparison of government debt levels across multiple countries over time. The color gradient highlights countries with high and low debt-to-GDP ratios, offering a straightforward way to compare debt levels across a broad set of countries and observe shifts over time.

3. **Part 3: Debt Trends Line Chart in Tableau**  
   This line chart focuses on selected countries, providing a continuous view of debt trends from 1995 to 2019. By showing how debt levels change over time, this chart reveals how different countries responded to global economic crises, offering insights into their fiscal policies and economic resilience.

Together, these visualizations provide a comprehensive view of global government debt trends, highlighting the diversity in fiscal policies and economic responses across different nations.

# Part 1: Working with web-based visualization tools and data

![image](https://github.com/user-attachments/assets/0427bb31-1ddc-4d14-9ffe-acaeb6e2317f)

The image shows the General government debt for various countries for the year 2023.


<!--
_A reminder that to get the Tableau visualization to render correctly on Github, you'll have to do a bit of editing of the code block once you paste it here.  As before, make sure to walk us through what you did in Tableau, and any thoughts or observations, etc._
-->

# Part 2: Government Debt Highlight Table

## Visualization Overview

This highlight table (heatmap) provides a comparison of government debt as a percentage of GDP across multiple countries over time, specifically from 1995 to 2019. Each cell represents the debt-to-GDP ratio for a given country and year, with color intensities indicating the magnitude of debt. Countries with higher debt-to-GDP ratios are highlighted in shades of orange, while those with lower ratios are in shades of blue, making it easy to spot trends and extremes in government debt across different economies.

## Story Behind the Data

The highlight table provides a powerful visual tool to understand the **distribution and concentration** of debt-to-GDP ratios across nations. Key insights from this visualization include:

- **Countries with Persistent High Debt**: Japan (JPN) and Italy (ITA) consistently have high debt-to-GDP ratios, shown in deep orange, indicating a reliance on government debt over time.
- **Countries with Low Debt**: Countries like Estonia (EST), Mexico (MEX), and Turkey (TUR) are represented in deep blue, indicating low levels of government debt compared to GDP.

This visualization provides a quick overview of debt levels and allows viewers to identify patterns at a glance, showing how different countries manage their government debt over time and highlighting the impact of global events.

## Chart Description

- **Columns**: Each column represents a year, showing data from 1995 to 2009.
- **Rows**: Each row represents a country.
- **Color Scheme**: An orange-blue diverging color scheme is used, with orange representing debt levels above 100% of GDP and blue indicating levels below 100%. The more intense the color, the further the debt level is from the 100% threshold, either above or below.

---

<div class='tableauPlaceholder' id='viz1730759721637' style='position: relative'><noscript><a href='#'><img alt='General government debt Source: OECD ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;Partb-GDP&#47;Generalgovernmentdebt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Partb-GDP&#47;Generalgovernmentdebt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;Partb-GDP&#47;Generalgovernmentdebt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1730759721637');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Source: **OECD**. This data visualization was created using **Tableau**.

<!--## Part three: create your own visualization

_Create another data visualization using the same data used earlier. DO NOT submit something that's just a minor modification of one of the visualizations already covered here. So, don't just modify the colors or labels of one of the earlier examples and call it good, or submit a slightly modified bar chart.  Instead, see what you can come up with on your own, and spend some time to try and create something that tells a story about the data._

_Summarize in a paragraph or two about the different methods of visualization, and how they compare / contrast to one another. Make sure you include all source information and explain the data well.  Talk about why you chose the third data visualization.  Be specific - keep your writeup relevant to the assignment, and avoid jargon-filled language that doesn't say anything useful._

_It's a good idea to go back and review your work.  Could someone follow your process and understand what you did?  Do you need to further connect any of the sections with a bit of text?  Is it something you'd be happy to have as an example of your work from the class?_
-->

# Part 3: Government Debt Trends Over Time: USA vs. Major Global Economies

## Visualization Overview

This visualization compares government debt as a percentage of GDP across the United States and other major global economies from 1995 to 2019. The purpose of this comparison is to illustrate how different countries manage their debt levels over time, particularly in response to significant global economic events, such as the 2008 financial crisis. By focusing on both high-debt and low-debt countries, this chart provides insights into the varied fiscal policies and economic resilience of different nations in comparison to USA.

## Story Behind the Data

This visualization tells a story of **economic diversity and response to crises**. The selected countries represent a range of fiscal policies, from high-debt tolerance to low-debt conservatism. Each country's government debt as a percentage of GDP reveals how it has responded to both global and domestic economic pressures.

- **Japan (JPN)** stands out as having the highest debt-to-GDP ratio, consistently surpassing 200% in recent years. This is largely due to Japan’s unique economic policies and the challenges of an aging population, which increase government spending on social services.
- **Estonia (EST)**, on the other hand, maintains one of the lowest debt-to-GDP ratios. This demonstrates a conservative fiscal approach, where the government relies less on debt financing, indicating a contrasting policy to that of Japan.
- **USA (USA)** shows a steady increase in debt, with notable spike during the 2008 financial crisis. These spikes reflect the US government’s approach of increasing spending to stabilize the economy during periods of crisis.
- **European Economies** like **Germany (DEU)**, **France (FRA)**, and the **United Kingdom (GBR)** have debt levels that vary, showing moderate increases. Germany, in particular, maintains relatively lower debt levels, while the UK and France display debt trends similar to the USA, with noticeable increases during recent crises.

This visualization highlights the varied fiscal responses and economic resilience of different countries in managing government debt, providing a global perspective on debt dynamics.

## Why These Countries Were Chosen

The selected countries represent a balanced and diverse range of economic policies and debt levels:

- **Japan (JPN)**: Known for its high debt-to-GDP ratio, representing a high-debt tolerance model.
- **Estonia (EST)**: Known for its low debt levels, representing a conservative fiscal policy.
- **USA (USA)**: A large economy with a moderate but rising debt profile, reflecting active fiscal intervention during crises.
- **Germany (DEU), France (FRA), United Kingdom (GBR)**: Major European economies with varying debt policies, representing different responses within the European region.
- **Canada (CAN)**: Provides a North American perspective alongside the USA, showing a moderate debt approach similar to European economies.

This selection captures a wide spectrum of debt management strategies, from high-debt tolerance to low-debt conservatism, and provides a comprehensive view of government debt management across regions and economic statuses.

## Chart Description

This line chart presents government debt as a percentage of GDP over time (1995–2019). Each line represents a different country, with distinct colors used to differentiate key countries in the story:

- **Red (Japan)**: Indicates consistently high debt levels.
- **Green (Estonia)**: Represents the lowest debt levels, providing a sharp contrast with high-debt nations.
- **Blue (USA)**: Shows moderate but increasing debt levels, highlighting the impact of economic crises.
- **Gray tones (Other countries)**: Used for Canada, Germany, France, and the UK, which display varied debt levels within the middle range.

### Key Annotations

- **2008 Global Financial Crisis**: A vertical line is added at 2008 to indicate the financial crisis, during which debt levels spiked for most countries, as governments increased spending to stabilize their economies.

This annotation help provide context for the spikes in debt, allowing viewers to understand the external events that influenced these trends.

---

<div class='tableauPlaceholder' id='viz1730763491533' style='position: relative'><noscript><a href='#'><img alt='Government Debt Trends Over Time: USA vs. Major Global EconomiesSource: OECD ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USAvsOthers&#47;USAvs_MajorGlobalEconomies&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='USAvsOthers&#47;USAvs_MajorGlobalEconomies' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USAvsOthers&#47;USAvs_MajorGlobalEconomies&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1730763491533');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Source: **OECD**. This data visualization was created using **Tableau**.

## Insights and Conclusions

This visualization demonstrates how different countries approach debt management and the impact of global events on government borrowing. Countries like **Japan** have sustained high debt levels without significant instability, largely due to domestic factors like low interest rates and strong internal demand for debt. In contrast, **Estonia’s low debt levels** suggest a cautious approach, with the government avoiding large-scale borrowing. **The USA and the UK** show similar patterns, with debt levels rising notably during economic crises, reflecting active fiscal responses.

By comparing these countries, this visualization provides a global perspective on government debt, highlighting the resilience or vulnerability of economies to high debt and the impact of key economic events on fiscal policies.

## Comparison with Heat Map in Part 2

While the highlight table (heatmap) provides a quick way to scan and compare debt levels across countries in specific years, the line chart in Part 3 offers a more detailed, continuous view of debt trends over time for selected countries.

- **Highlight Table (Heatmap)**:
  - **Strengths**: Allows for easy comparison across many countries in a compact format. The color intensity helps quickly identify which countries have high or low debt-to-GDP ratios at specific points in time.
  - **Limitations**: It’s less effective at showing continuous trends or how debt levels evolve smoothly over time. The discrete nature of cells limits the viewer’s ability to trace changes within individual countries across all years.

- **Line Chart (from Part 3)**:
  - **Strengths**: The line chart in Part 3 provides a clearer view of each country’s trend over time. It’s ideal for tracking changes in debt and highlighting responses to specific economic events like the 2008 financial crisis.
  - **Limitations**: The line chart is more suitable for a smaller selection of countries due to potential clutter when adding too many lines, whereas the highlight table can display many countries without becoming overwhelming.

In summary, both visualizations serve unique purposes. The highlight table is excellent for comparing a large set of countries at a glance, while the line chart allows for in-depth analysis of trends in specific countries over time. Using both together provides a comprehensive perspective on government debt across nations.






