# Data Visualization Critique & Re-design

For this assignment, I decided to critique the chart in the [CNBC article](https://www.cnbc.com/2021/10/08/where-the-jobs-are-september-2021-chart.html) titled "Here's Where the Jobs Are - in One Chart". I have always been interested in policy discussions surrounding education, and am curious how the COVID-19 pandemic and related political tensions regarding mask mandates and vaccine mandates may affect our public schools. The artile makes the point that "[p]ublic schools often bouy the September jobs report as \[public school districts\] hire teachers, bus drivers, administrators, and other staff back for the start of the fall term... That did not happen as it normally does in 2021". However, the provided chart does not make it clear the impact of public school employment on overall employment numbers. Instead, the reader only finds out through further reading that Government employment includes public education employmnet at the state and local levels, with overall employment dereasing by 144,000 in local government education and 17,000 in state government education, seasonally adjusted.

In critiquing the visualization using Stephen Few's Data Visualization Effectiveness Profile, I identified both some pros of the visualizations that I'd like to keep, as well as several areas for improvement. First, the visualization is easy to interpret; the bar graph format is familiar to readers and the usage of color immediately draws a distinction between sectors with job gains versus job losses. this is something that I'd like to keep in my re-design so that the resulting graphic is still accessible for the general readership of CNBC. There isn't a lot of clutter, although the chart is distintly missing a key note that the data are seasonally adjusted (potentially misleading readers). I may add a note to clarify the seasonal adjustment to improve the accuracy of the chart. Of course, one key area of improvement would be to break dow the public education numbers to directly support the key points of the article. Specifically, I think it would be helpful to break down the 'Government' category into state education, local education, and other government. I also realized that it would be helpful to provide some context as to what the 'September boost' can be expected to look in a normal (non-pandemic) year. This inspired me to look for prior years' data from the same source (Bureau of Labor Statistics) that could provide a visual benchmark of sorts in my re-design.

# Wireframing 

Below is my wireframe for a re-design of the visualization. In creating this wireframe, I focused my efforts on presenting and highlighting the public education numbers, as well as finding a way to provide additional context/baseline from other 'normal' years. I chose 2019 as the most recent, pre-pandemic year for the reference numbers. These figures were acquired from the same source, bureau of Labor Statistics, and were similarly seasonally adjusted. I also tried to use bolding to emphasize the two public education rows, although that is somewhat difficult to see in a hand-drawn format.

![My Draft Redesign!](/wireframe.jpg)

# Feedback

I interviewed three friends for feedback on my wireframe. Below is a summary of their response.

1. At first glance, what do you think this is? 
(A) I don't know.
(B) September job report.
(C) Whether jobs increased or decreased based on sector.

2. What do you think this chart is telling you?
(A) Change in jobs in different industries 
(B) It's weird that the public education sector has shown a loss of jobs in September 
(C) Local/public education employment is down 

3. Was there anything you found surprising or confusing?
(A) It was confusing how to interpret the chart at first because there's no axis. I thought the dots were the anchors and the lines were the direction of movement, so it looked like each line was starting at different points.
(B) The phrase 'public education' was confusing; it wasn't clear that this is referring to a job sector rather than the general state of public education in society
(C) The dashed lines - do they show some increase in jobs but the overall net was decrease? 

4. Who do you think the intended audience is?
(A) the general public 
(B) Wall Street Journal readers
(C) the public? 

5. Is there anything you would change or do differently?
(A) Make it clear where the anchors of each line is. Maybe use a solid dot to represent the 'start' of the line. Maybe add an axis to make it clear.
(B) Find a way to focus only on education, if that's the main story being told. Draw the focus on the comparison with the 2019 baseline. Are the other sectors important to the story? Maybe it would be interesting to see the comparison with September 2019 for all other sectors as well? 
(C) Add an axis to make it clear that all lines are starting at 0 net change. Maybe add a legend to clarify that the dashed lines are there for baseline comparison.

Across the board, it was clear that the design of the chart was a little confusing, perhaps because I tried to oversimplify. Friend A initially did not know what the chart is representing because they had skipped over the phrase in parentheses in the title. The lack of an axis denoting 0 was a common source of confusion for all respondents. When I asked whether it's helpful to include the September 2019 data as comparison, the general response is 'yes', but the way the information is presented seems to cause confusion. 

The interviews were really helpful in informing my next steps. My priorities for the redesign would be 1) make it clear what the data are showing (net change in the number of jobs by sector); 2) add an axis to denote net 0 change; find a way to further de-emphasize other sectors and emphasize education; and 4) finding a way to simplify the comparison with 2019.


# Re-design

Below is my re-designed version of the chart. 

<div class='tableauPlaceholder' id='viz1636423412371' style='position: relative'><noscript><a href='#'><img alt='Public education jobs usually see growth in September, lags instead in 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;em&#47;employment_trends&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='employment_trends&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;em&#47;employment_trends&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1636423412371');                    
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
