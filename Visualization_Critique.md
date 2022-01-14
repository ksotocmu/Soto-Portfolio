### Step One: Find a Data Visualization 

When selecting a data visualization I wanted to choose one that was something you might see in an everyday scenario, and not just a curated bad data visualization, so I found one in the wild. As I was reading Bloomberg News I came across a visualization about the changing labor market that compared unemployment rates and month to month changes in average hourly wage. To reporduce the data I downloaded the Bureau of Labor Statistics unemployment numbers and numbers on average hourly wage change from month to month for the same time period. This article and the attached data visualization fascinated me as there are two different audiences that are intended to consume it. The first is the public financial news reading audience which is a far more wide ranging audience including policy makers, amateur investors, concered parents, and everything in between. The second is the financial professional audience which includes financial analysts, economists, investors, and other financial occupations. I wanted to consider how this effected the presentation of the data. 


Article - https://www.bloomberg.com/news/articles/2022-01-07/u-s-adds-fewer-jobs-than-forecast-unemployment-rate-falls 

![Bloomberg Bad Data Viz](https://user-images.githubusercontent.com/74934048/149539485-5965826e-121b-4237-a7c6-7bc06e9e7ca6.png)


### Step Two: Critique the Data Visualization 

My first impression upon seeing the data visualization from Bloomberg was it took me a moment to make sense of it. An area chart of the national unemployment rate is stacked on top of a chart illustrating the change in hourly wage on a month to month basis. Initially however I thought the bar chart illustrated the month on month change in the unemployment rate it wasn't until a more in depth viewing I saw the key indicating the bottom chart was concerned with wages.  The unemployment rate is indicated by the key to be the items in red, but the area color of the area chart is blue which is confusing as the only  item in red is the 3.9% indicator on the y-axis of the top chart. The lowest number on the y-axis of the top chart appears to be that 3.9% but there are values from the beginning of 2020 that appear to be lower than that. I was most confused by the y-axis of this chart, in both the top and bottom section of the chart the y-axis indicates percent, but there is no mention that the percent being measured is of different things, with the top chart measuring the percent of the workforce that is unemployed at a given time and the bottom chart measuring the percent change in average hourly earnings from month to month. The bottom section of the chart also has a y-axis that can dip below zero and indeed does on two instances that are measured, however since the top section of the chart has no zero value and the bottom does the axis initially appears almost like one single y-axis rather than two. This confusion from the lack of a zero value on the top axis is exacerbated by the 6.0 value butting up against the line separating the chart which serves as the divider between the two charts as well as the x-axis for the top chart and the top of the y-axis for the bottom chart so a 6 is found where a zero is expected. The text on the bottom chart indicating the wage growth highlighted "matches the biggest advance since April" is helpful in displaying what the chart is trying to convey, but the chart itself is not effective in conveying it as the bar looks like a blip since the chart is compressed. While I understand what the designer was trying to do by showing the hourly earnings chart below the unemployment rate chart so that the time from one chart aligns with the time on another, I don't think it was effective here. The sacrifices made to the clarity of both charts makes the overall presentation feel  jumbled and less intuitive. The visual presentation feels overly compact, as if the designer was trying to fit two charts into a figure designed for one.  The labeling of the chart makes the axis difficult to decipher and while the subtitle is descriptive it's not clear what the title is trying to show about wages.


The primary audience for this visualization are those interested in financial news. That could be economists, financial advisors, professional and amateur investors, or just citizens hoping to stay engaged and read the news. The audience may be partially motivating of the presentation of this chart as Bloomberg the parent company of Bloomberg News is most famous for their Bloomberg terminal which provide financial analytics to investors in a similarly compressed format. I believe this is why clarity why sacrificed for condensed visual presentation as charts like these are more common on machines like the Bloomberg terminal which brokers and investors are accustomed to viewing. This however leaves out a critical part of their audience and can make the information feel overly complicated and inaccessible. While those investors may be able to understand this condensed visual format, those not accustomed to the terminal style of charting will likely struggle on their first pass viewing this chart. Therefore this chart is partially effective in that some of the audience Bloomberg is seeking to reach will be able to understand the information they are trying to convey, it is also ineffective to consumers of financial news who aren't well versed in the Bloomberg terminal style of visualization. Since this article was shown in their news section it should have broad perceptibility and I don't believe it clears that threshold.

 

### Step Three: Wireframe a Solution
The most significant issue I found with the visualization from Bloomberg was clarity. It seemed in order to place both of the concpets the visualization wanted to convey over the same time period some of the perceptability was lost in the process. The visualization also never fully committed to being two separate visualizations or just one and seeimingly tried to do both. This in mind I saw two ways forward in wireframing a solution. The first was to fully merge the two visualizations into one chart with completely shared axes and the second was to create two separate charts that would be linked together via their interactivity.  There were challenges to each approach, the first approach presented issues with the clarity of the y-axis. While both percent change in hourly wage and unemployment rate are measured on the same scale, percent, they are different measurements. I wasn't sure how to appraoch this conundrum so I kept the y-axis as simply "Percentage" and added the clarity to the key. For the second option it had to be clear that these two measurements were linked and I wanted to add interactive elemnets to allow users to explore their link. I wireframed both options and showed them to two users and gathered their feedback.


### Step Four: Test Your Solution


#### Version 1

![V1_TSWD_Visual_Critique](https://user-images.githubusercontent.com/74934048/149545680-f703872d-5bb4-494b-85c8-e00075932681.jpg)


#### Particpant 1: Anna, 25 years old, she/her, journalist 

##### - Can you tell me what you think this is?
It looks like you’re showing two things: percent change of hourly wages (in yellow) and unemployment rates (in blue) over time. 
##### - Can you describe to me what this is telling you?
The chart is showing how despite the steep drop off in unemployment rates since the start of the pandemic, there’s been a positive percent change in hourly wages (before the start of the pandemic, the percent change was flattened). 
##### - Is there anything you find surprising or confusing?
I think the chart could point to factors contributing to the tightening job market in the subtitle, depending on what’s valuable to the reader (labor shortages forcing wages up, etc.) I initially found it confusing that the yellow line was percent change, since I initially didn’t read the legend closely enough. Is there a way this could be emphasized?
##### - Who do you think is the intended audience for this?
The audience is probably someone with some knowledge of economics. With annotations, the chart would probably be for the average “lay person.” 
##### - Is there anything you would change or do differently?
Maybe add a subtitle! Looks good though!


#### Particpant 2: Jeff, 62 years old, he/him, systems engineer

##### - Can you tell me what you think this is?
It appears to be the unemployment rate during the pandemic and the the change in hourly wage as unemployment changes  
##### - Can you describe to me what this is telling you?
I see there was a big jump in unemployment when the pandemic started and then unemployment slowly dropped again, it looks like there was also a big jump in wages when the pandemic began.  Now it looks like wage change is stagnating and unemployment is at 3.9% so we're back to where we started.
##### - Is there anything you find surprising or confusing?
I didn't expect to see a big jump in wages when the pandemic started but a lot of lower wage workers got laid off so that makes sense. I'm not sure what I'm supposed to take away from this graph. I thought for a second the orange part was the change in unemployment since they're similarly shaped but I saw the orange means hourly wage. 
##### - Who do you think is the intended audience for this?
It seems like something I would see in the Financial Times or Wall Street Journal but I've seen graphs like this in the news. 
##### - Is there anything you would change or do differently?
I might change the look of one since the simiar shapes were a bit confusing at first. 



#### Version 2


![interactive_TSWD](https://user-images.githubusercontent.com/74934048/149547785-c4d3eb42-49cb-4996-84a5-300046e57d02.jpg)
![drag_highlight_TSWD](https://user-images.githubusercontent.com/74934048/149547977-32bbeb9b-935e-458c-b4d3-80da9145b6f2.jpg)
![highlighted_section_TSWD](https://user-images.githubusercontent.com/74934048/149548303-16b61623-372b-48e3-bee7-a2d1f954155f.jpg)


#### Particpant 1: Anna, 25 years old, she/her, journalist 

##### - Can you describe to me what this is telling you?
There are two charts. One is an area chart showing the unemployment rate since before the pandemic. The other is a column chart showing the percent change in hourly wage, on the same time scale as the other chart. It looks like this second chart includes negative percent change. You can highlight an area and zoom in closer to compare the two charts. 
##### - Is there anything you find surprising or confusing?
I think it’s interesting that there’s positive percent change in wages during the height of unemployment, possibly due to offices with relatively higher wages allowing their employees to work remotely while other establishments, like restaurants, shut down in 2020. Also, there’s a positive percent change in wages now that unemployment is decreasing, possibly due to labor shortages.
##### - Who do you think is the intended audience for this?
These charts are straight forward, but don’t have much context. Depending, these charts might be appropriate in a report, journalistic article, or for the average person, especially if they’re contextualized.
##### - Is there anything you would change or do differently?
I might include subtitles to pull out interesting details or provide context for the chart. I might add a source and credit line.



#### Particpant 2: Jeff, 62 years old, he/him, systems engineer

##### - Can you describe to me what this is telling you?
Now there is a graph for unemployment and a graph for hourly wages. Unemployment is going down looking at the sloping line and hourly wages are all over the place. It looks like you can drag your mouse and zoom up to a spot on the chart. I like that. 
##### - Is there anything you find surprising or confusing?
I'm not sure if I can zoom up on both of the graphs or just one but I think that's just the drawing. It looks like the scales changed after zooming which is interesting. Also that flag in the bottom chart is hard to read. Can I click one of the bars in the bottom graph, if I do what happens?
##### - Who do you think is the intended audience for this?
It looks like these graphs I might see on my banking app or something like that. These seem more detailed than the first. Still not sure what I'm supposed to take away from these. 
##### - Is there anything you would change or do differently?
I like that you changed the orange from a line to bars, so I'd keep that. I'd like to see them tied together in some way since the two graphs just seem like to graphs. 



##### Results

The feedback for both versions is similar to what I expected, and some of the issues inherent in each of the approaches. I didn't expect the area chart approach for the hourly wage to be confusing, but after hearing the responses it made sense how the shape could throw someone off. If I were to take the approach of using two separate visualizations the interactivity piece would be key to linking them together. There was consistent feedback in both versions about what the reader is intended to learn from the visualizations so in a final version I'll add subtitles. The more general y-axis in the first version didn't seem to present as much of a dilemma as I initially expected, but it's very important that the key is clear and prominent.


### Step Five: Build Your Solution

<div class="flourish-embed flourish-chart" data-src="visualisation/8377503"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

##### Discussion

In my final solution I chose to utilize the single merged data visualization method which I didn't expect as I was so hard on it in my critique. When the merger between the two was clearer sticking to one data viz didn't cause much information loss. This is however partially a technical limitation as Flourish lacked the ability to specify a data range and view subsections of the data that way. While you can look at any individual point in time and all points you can't choose a specific range which is what I would have wanted to pursue the multiple visualizations approach. Otherwise the two seem like disparate charts. I added a subtitle as I wanted to give the user an idea of why the chart exists and what information the chart wants to convey. It's always shocking to me just how much mileage you get out of effective labeling and titles. I also made the key larger, more explicit, and entirely interactive so either unemployment or change in hourly wage could be viewed independently. 
