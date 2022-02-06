# Step one: find a data visualization
## The chart I chose
IC3 Complaint Statistics 2014-2018 
from the report ["2018 INTERNET CRIME REPORT"](https://www.ic3.gov/Media/PDF/AnnualReport/2018_IC3Report.pdf)

![image](/original.png)

## Reasons why I chose it

I am choosing this chart because I looked through several articles and this visualization cauught my attention suddenly. There is a globe in the background. Apparently, the author wanted to create something special. However, after analyzing it carefully, I realized that there are big problems about this visualization that I want to change, so I chose this one.

# Step two: critique the data visualization
## How does this method compare to the Good Charts method? 
This method is a more comprehensive one compared to the good charts method. This method consists of both informative and emotive aspects. The Good Charts method focuses more on the visual aspect of a chart, and it does involve more detailed questinons about the visual aspect of a chart. However, this method also focus on the information aspect of a chart, for instance, usefulness and completeness of the data.

After doing this critique, I realized that the chart is showing very useful data to the report readers, but the problem is that there are too much unuseful visual elements in the chart, like the globe in the background and the arrow on the top. Less is more. In my redesign, I am going to eliminate those elements and show only what is necessary to convey the information to the audience. Besides, the figures in the graph are still hard to read, since we can't easily see the trend from a plot like this. The visualization didn't help at all. 

# Step three: wireframe a solution
## Sketch

In order to I redesigned two versions. The first one is a combination of a line chart and a bar chart, while the second one is a concatenation of two bar charts. I personally prefer the first one, but I still need opnions from others in the interview, which I'll do in step 4.
![image](/sketch.png)



# Step four: Test the solution
## First Interviewee
- Can you tell me what you think this is?

The interviewee first asked what is IC3, and then interpreted #complaints and losses as the complaints it received and the losses of IC3. Without the context of the original report, the interviewee misunderstood the title and the data. 

I explained to her what the data really meant, which took quite a few questions. This suggests that this plot depends a lot on the original report.

- Can you describe to me what this is telling you?

The interviewee could see that the number of complaints IC3 received and losses were increasing every year.


- Is there anything you find surprising or confusing?

2 y-axis in the same plot is quite surprising to her. The interviewee first wondered why I used line chart for losses and bar chart for complaints, but then thought it made sense, because one is above the other. This design is better than using line chart for both data or using bar chart for both data.

- Who do you think is the intended audience for this?

The department in charge of internet crimes.

- Which one do you prefer? Is there anything you would change or do differently?

If there is some kind of correlation or other relationship, the first design is better. Otherwise, the second design is better. She said that she definitely prefer the first design. The first sketch is good-looking and there is nothing she wanted to add to it.

## Second Interviewee
- Can you tell me what you think this is?

The interviewee first asked what is IC3. After I explained to him, he said that this is a histogram that shows that complaints and losses are increasing.

- Can you describe to me what this is telling you?

He thought that IC3 was almost done, because misunderstood that the data was complaints about the IC3 and their losses. So, I had to tell him the real meaning of the data to keep our conversation going on.

- Is there anything you find surprising or confusing?

For the first sketch, he was confused about the relationship between complaints and losses. He even questioned if complaints and losses were comparable. For example, if there are more complaints than losses.

- Who do you think is the intended audience for this?

Maybe to any high level officials that were in charge of this issue.

- Which one do you prefer? Is there anything you would change or do differently?

The interviewee said that the second one is a little hard to read because you have to go back and forth between two plots, while the first one is easier to read. In the first sketch, he was not sure about the relationship between the line char and the bar chart, saying that he needed more information to judge.

## Summary: similarities and differences

Both of them mentioned that the plot is hard to understand at the first glance. Without the help of the report context, readers couldn't understand the meaning of IC3, complaints and losses. After I explained to them what they are, they could understand the plot and its implication.

Both mentioned that the combination of a line chart and a bar chart is quite innovative, which they don't often see. One of the interviewee said it was beautiful, the other said it was a little surprising. But they both loved this design overall.

## What to change heading into step five

Apart what I changed in the sketch (already mentioned above), I am making the following changes in the final visualization:
1. Move legends information into the graph rather than put it on the right side so that the readers can tell which one is complaints and which one is losses more easily.
2. Alter the phrasing of title and legend so that the plot can be understood without the context of the report. The title will be "FBI's IC3 received increasing complaints of Internet crime". This tells the reader that IC3 is a part of FBI and their job is to receive crime reports.
3. Adding proper colors to the chart.

# Step five: Build your solution
I completed the visualization with Tableau.

<div class='tableauPlaceholder' id='viz1644177681717' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='assignment34_16441776035710&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644177681717');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
