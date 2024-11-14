| [home page](https://eraasinglaa.github.io/tswd-portfolio-era/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Redesigning a Data Visualization: Paid Vacation Days by Country

In this project, I undertook an assignment to analyze and improve a data visualization showing the total paid vacation days across countries. The original visualization, sourced from Resume.io, uses a world map to highlight differences in paid leave policies globally. My goal was to critique this visualization based on established data visualization principles, identify areas for improvement, and create a redesigned version using Tableau.

This write-up documents the entire process, from the initial critique using Stephen Few's Data Visualization Effectiveness Profile to the development of a redesigned visualization that emphasizes clarity, comparability, and user interactivity. By combining a choropleth map and a bar chart, my redesigned dashboard provides an engaging yet informative way to explore vacation policies by country, with clear distinctions between paid leave days and public holidays.

Below, you will find a summary of my redesign process, user feedback, and final visualizations, including insights into how the redesign better serves its intended audience.

## Step one: The Original Visualization

For this project, I selected a data visualization on the **total paid vacation days worldwide** created by Resume.io. The original visualization uses a world map to illustrate the total paid vacation days for each country, combining paid leave days and public holidays. I chose this visualization because, although visually engaging, it presents challenges in readability and accuracy that I believed could be improved upon. You can view the original visualization [here](https://resume.io/blog/which-country-gets-the-most-paid-vacation-days) or in the screenshot below:
<img width="700" alt="image" src="https://github.com/user-attachments/assets/11fb8701-a639-4cf0-9bb2-987c1a3fdab0">

---

## Step two: Critique Using Stephen Few’s Effectiveness Profile
Using Stephen Few's criteria, I evaluated the original visualization across seven dimensions: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. My main findings were:

- **Strengths**: The original visualization is visually engaging and offers an accessible overview of global vacation policies.
- **Weaknesses**: The color gradient used makes it difficult to differentiate countries with similar vacation day counts, and the high density of annotations clutters the map, making it hard to interpret quickly.

**Insights Gained**: Based on this critique, I planned to simplify the color scheme, reduce annotation clutter, and add a secondary visualization format (e.g., bar chart) to clarify quantitative comparisons across countries.

## Step Three: Sketching and Wireframing the Solution

After identifying key areas for improvement in the original visualization, I created a rough sketch in Excel to explore alternative ways of presenting the data. This initial sketch was a simple prototype to test whether a more quantitative approach, like a bar chart, could better convey the differences in total paid vacation days across countries. Although I knew the final design in Tableau would be more refined, this sketch provided a glimpse into how the data could be organized more effectively.

### Key Ideas and Rationale

1. **Replacing the World Map with a Bar Chart**:
   - The bar chart format immediately allows for a clearer comparison of countries by visually ranking them based on total paid vacation days.
   - By ordering countries from highest to lowest vacation days, viewers can quickly identify which nations offer the most generous paid leave. This sequential arrangement also reduces the cognitive load of comparing scattered data points across a map.

2. **Using a Cleaner Color Scheme**:
   - I opted for a simplified color scheme with distinct intervals in the Excel sketch to make the differences between countries more visible.
   - This choice helps in distinguishing countries with similar vacation day counts and avoids the visual confusion often caused by subtle gradients on maps.

3. **Adding Contextual Information**:
   - Although not fully realized in the sketch, I considered using a sidebar or supplementary notes in the final design to provide regional summaries and insights. This additional context could help viewers understand why certain regions have high or low vacation days, linking it to cultural or policy factors.

### Insights Gained from the Sketch

Creating this prototype helped me validate that a bar chart could facilitate better quantitative insights than a map alone. The sketch demonstrated how a straightforward, ranked bar chart can highlight comparative data more effectively, setting the foundation for an improved Tableau dashboard. With this basic structure in mind, I moved forward to implement a more interactive, polished version in Tableau, incorporating the feedback from this initial test.

*Below is an early sketch of my revised layout.*
<img width="1409" alt="image" src="https://github.com/user-attachments/assets/70e60c68-b3d3-4661-824a-ccf46d819146">

---

This sketch laid the groundwork for the final dashboard in Tableau, where I combined the bar chart with an interactive map for a more comprehensive view.

## Step four: User Feedback

### Questions to Ask

Here are the questions I used to guide the feedback sessions:

- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?

I shared the redesigned visualization with two individuals and documented their responses as follows:

| Question                                  | Interview 1 (Student)                                                                                                                                                                                | Interview 2 (Professional)                                                                                                                                   |
|-------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **Can you tell me what you think this is?** | "It looks like a comparison of countries based on the number of paid vacation days they offer."                                                                                                               | "This seems to be showing which countries provide the most vacation days and breaks it down by paid leave and public holidays."  |
| **Can you describe to me what this is telling you?** | "The map shows how vacation days vary globally, and the bar chart ranks countries by total days off, split between paid leave and public holidays. It gives a quick way to see which countries are generous." | "It’s showing total vacation days by country and lets you compare them by type of leave. The split of vacation days is helpful." |
| **Is there anything you find surprising or confusing?** | "It was surprising that some countries, like the U.S., have so few days off. Also, I had to hover over the map to see details, which wasn’t obvious at first."                                               | "It’s clear overall, but I was confused at first about how to view details. Maybe a label or guide would help."                 |
| **Who do you think is the intended audience for this?** | "Anyone interested in global work policies or people considering working abroad. Also, HR professionals might find it helpful."                                       | "It seems intended for a general audience, especially those interested in work-life balance or international work benefits."     |
| **Is there anything you would change or do differently?** | "Maybe add a brief instruction to indicate that you can click on the map or hover for details."                                                                         | "A title change could help, something that clarifies this is about vacation policies. Also, slightly larger text would be nice." |

### Results

**Key Insights from Feedback:**

Both users understood the dashboard's purpose and found it helpful for comparing global vacation policies. They appreciated the breakdown between paid leave days and public holidays, which offered more insight into how different countries structure vacation policies. However, they provided valuable feedback for improvement.

**Synthesis:**

- **Patterns in Feedback**:
  - Both interviewees found the dashboard clear in its overall purpose but mentioned that some instructions or guidance could enhance usability. They initially weren’t sure that the map was interactive until they started exploring.
  - Both users found the map-to-bar-chart interaction helpful once they figured it out and liked the ability to see the specific breakdown between types of leave.
  - They noted that a slight increase in text size could improve readability, especially for older users or those viewing on smaller screens.

- **Learnings from Feedback**:
  - **Interaction Cues**: To improve clarity, I realized that adding a brief note or tooltip explaining that users can interact with the map and bar chart might help new viewers engage with the dashboard immediately.
  - **Title and Text Adjustments**: A clearer title, such as "Global Paid Vacation Days: Country Comparisons by Leave and Public Holidays," would set expectations right away. Additionally, slightly increasing the font size could enhance readability for a broader audience.

**Design Changes Based on Feedback**:
- **Add Interaction Guide**: Include a small note below the title (e.g., “Click on the country to view respective information in the bar chart”) to guide users.
- **Refine the Title**: Update the title to emphasize that this is a global comparison of vacation days.
- **Increase Text Size**: Slightly adjust font sizes for better readability, especially on key labels and in tooltips.

These adjustments aim to make the visualization more intuitive for first-time users, ensuring they can immediately understand and interact with the data without additional explanation.


I shared my initial sketches with few individuals and did critique exercise during the class as well. Here is their documented feedback:

1. **User 1** (student, mid-20s): Thought the bar chart made it easier to compare countries but found the sidebar text too detailed.
2. **User 2** (adult, late-50s): Liked the simplified color scheme but suggested increasing font size for readability.

**Patterns in Feedback**: Both users found the bar chart more effective than the map for comparing vacation days across countries, and both suggested focusing on clarity and simplicity.

**Design Changes Based on Feedback**:
- Reduced the amount of text in the sidebar and used bullet points for quick insights.
- Adjusted the font size to improve readability, especially for older viewers.

## Step 4: Building the Solution in Tableau

### Purpose and Design Choice

In my redesigned dashboard, I aimed to enhance clarity and usability while maintaining an engaging overview of global vacation policies. This dashboard combines a **choropleth map** and a **bar chart** to visualize total paid vacation days per country, segmented by **paid leave days** and **paid public holidays**.

- **Choropleth Map**: This map provides an at-a-glance, global overview of vacation policies. By color-coding countries based on the total paid vacation days, viewers can quickly identify regions with the most and least generous policies.
- **Bar Chart**: The bar chart complements the map by offering detailed, ranked information. It allows users to see the exact breakdown of each country's vacation days, distinguishing between paid leave days and public holidays. This format also makes it easier to compare countries directly, which was challenging in the original visualization.

### Why These Visualizations?

I selected the choropleth map and bar chart because they work well together to balance **overview** and **detail**:

- **The map** is ideal for quickly spotting global patterns, such as clusters of high or low vacation day totals in specific regions (e.g., Europe and Africa).
- **The bar chart** provides detailed comparisons and breaks down the types of paid vacation days, highlighting how some countries achieve high totals through public holidays, paid leave, or a mix of both.

This combination allows viewers to interact with the data at different levels, enabling them to explore overall trends or focus on specific countries of interest.

### What I Attempted to Show or Do Differently

My goal with the redesign was to address key weaknesses in the original visualization while ensuring the data story remained compelling and accessible. Here are the main improvements:

- **Improved Comparability**:
  - The bar chart provides a clear, ranked view, making it easy to see where each country stands in terms of total vacation days.
  - The breakdown of paid leave and public holidays adds context, showing that countries like Iran achieve a high total through a unique mix, while others, like San Marino, rely more on standard leave.

- **Enhanced Readability**:
  - By using a Green-blue gradient scale on the map, I ensured that countries with similar vacation days remain distinguishable. The countries with low paid leaves are red while countries with higher paid leaves are blue which makes the comparison for viewers easy.
  - I reduced clutter by using tooltips on the map for country-specific details, which keeps the dashboard clean while allowing users to access more information as needed.

- **User Interactivity**:
  - Viewers can click on a country in the map to highlight corresponding data in the bar chart. This interactivity helps guide users through the data without overwhelming them with excessive text or annotations.

*Below is the final redesigned visualization:*
## **"Global Paid Vacation Days: Country Comparisons by Leave and Public Holidays"**
<div class='tableauPlaceholder' id='viz1731557218070' style='position: relative'><noscript><a href='#'><img alt='Countries Vacation Days ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Va&#47;VacationDaysbyCountry_17315555578710&#47;CountriesVacationDays&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='VacationDaysbyCountry_17315555578710&#47;CountriesVacationDays' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Va&#47;VacationDaysbyCountry_17315555578710&#47;CountriesVacationDays&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1731557218070');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='827px';}
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
---
### Summary
In this redesign, I aimed to tell a story about global work-life balance policies by revealing the differences in vacation entitlements worldwide. By integrating the map and bar chart, I provided a balance of visual appeal and detailed insights, making the dashboard both informative and engaging. This structure allows users to gain a broad understanding or dive deeper into specific country data, enhancing the overall utility and impact of the visualization.






