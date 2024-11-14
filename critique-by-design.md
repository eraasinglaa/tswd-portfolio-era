| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Redesigning a Data Visualization: Paid Vacation Days by Country
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: The Original Visualization

For this project, I selected a data visualization on the **total paid vacation days worldwide** created by Resume.io. The original visualization uses a world map to illustrate the total paid vacation days for each country, combining paid leave days and public holidays. I chose this visualization because, although visually engaging, it presents challenges in readability and accuracy that I believed could be improved upon. You can view the original visualization [here](https://resume.io/blog/which-country-gets-the-most-paid-vacation-days) or in the screenshot below:
<img width="700" alt="image" src="https://github.com/user-attachments/assets/11fb8701-a639-4cf0-9bb2-987c1a3fdab0">
---

## Step two: Critique Using Stephen Few’s Effectiveness Profile
Using Stephen Few's criteria, I evaluated the original visualization across seven dimensions: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. My main findings were:

- **Strengths**: The original visualization is visually engaging and offers an accessible overview of global vacation policies.
- **Weaknesses**: The color gradient used makes it difficult to differentiate countries with similar vacation day counts, and the high density of annotations clutters the map, making it hard to interpret quickly.

**Insights Gained**: Based on this critique, I planned to simplify the color scheme, reduce annotation clutter, and add a secondary visualization format (e.g., bar chart) to clarify quantitative comparisons across countries.

## Step three: Sketching and Wireframing the Solution
After identifying areas for improvement, I sketched this layout in Excel to explore alternative ways of presenting the data. Since, it's just a rouh sketch I knew that in Tableau I could make it lot better. It was just to get the glimpse if it could offer better quantitative insights. Key ideas included:
- Replacing the world map with a bar chart to facilitate clearer comparisons. I really liked how I could easily order the countries based on the number of total paid vacation days.
- Using a cleaner color scheme with distinct intervals to make differences more visible.
- Providing contextual information through a sidebar with regional summaries and insights.

*Below is an early sketch of my revised layout.*
<img width="1415" alt="image" src="https://github.com/user-attachments/assets/2a994b02-c438-4a48-a630-2ce1e6c5490f">


## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |


Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

I shared my initial sketches with few individuals and did critique exercise during the class as well. Here is their documented feedback:

1. **User 1** (student, mid-20s): Thought the bar chart made it easier to compare countries but found the sidebar text too detailed.
2. **User 2** (adult, late-50s): Liked the simplified color scheme but suggested increasing font size for readability.

**Patterns in Feedback**: Both users found the bar chart more effective than the map for comparing vacation days across countries, and both suggested focusing on clarity and simplicity.

**Design Changes Based on Feedback**:
- Reduced the amount of text in the sidebar and used bullet points for quick insights.
- Adjusted the font size to improve readability, especially for older viewers.

### Step 4: Building the Solution in Tableau

Based on my sketches and feedback, I created the final visualization in Tableau. Key features of the redesign include:
- **A bar chart** showing total paid vacation days per country, ranked from highest to lowest.
- **A simplified color palette** with distinct shades to differentiate levels of paid vacation days.
- **Tooltips for detailed data** when hovering over each country, showing breakdowns of paid leave and public holidays.
- **Regional summaries** providing context for differences across continents.

*Below is the final redesigned visualization:*
<div class='tableauPlaceholder' id='viz1731555685727' style='position: relative'><noscript><a href='#'><img alt='Countries Vacation Days ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;2Q&#47;2QM6K9MBZ&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;2QM6K9MBZ' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;2Q&#47;2QM6K9MBZ&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1731555685727');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='827px';}
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>







