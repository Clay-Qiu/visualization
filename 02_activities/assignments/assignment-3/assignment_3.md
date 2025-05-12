# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify:
- 
- The Excel was used to generate the visualization. It's mainly for the traffic control department, but also for the public to understand the trending for the cycling status in Toronto. The visualization includes the average daily data of the bicycle counts from 1994 Jun to 2025 Mar for each month, and also the in total counting each year. I did necessary cleaning to remove repetible data and trafserd missing data to N/A to avoid misunderstanding. Otherwise, the only calculation used was average and visualized with PivotTable function in Excel. The minimal calculation helps the visualization reproducible. The visualization uses red as more cycling counts and blue as less, with the accurate numbers on each block to keep the data were visualizaed accurately and honestly, which also pleased to look at without misunderstanding.
-  For visualization using Python, I choose the bar chart to present the same data as the excel. But I put each year's monthly sum daily average cycling counts in the same bar that labeled with different colors. To increase the accessibility, I add the data for each sections. But for shom bery short bars, adding the data number make it unreadable. So I used the ploty library to make it inactive. So that for the small bar, by putting the mouse on to it, the data number will shows up. Also the year and which month. I add the markdown and comments for the codes to make it reproducible. But, There are some data points missing, whcih makes the total length for each year's bar actually not comparable. Compare with the heatmap using Excel, which shows missing data as N/A, I can't add N/A to this bar plot. Bar plot may not the best visualization choice for this dataset. The interactive bar plot also give audiences to have a choice to explore the data and find the missing data points. Maybe I can add the missing month's data points as a figure legened to make it better.
- The data was published online with reviewed on the City of Toronto’s Open Data Portal (https://open.toronto.ca/dataset/permanent-bicycle-counters/). By showing the clear data range I used, it can be easily reproduced and accesssible. Traffic control department may be impacted by my visuialization to decide if they need to set more bicycle routes and set necessary signs to remind vichles drivers to notice bicycle drivers to avoid potential accidents. This can also be used to show to the vistors which weather is suitable to ride a bicycle to make a city tour.  I choose to use the heatmap and include counts, year and month. Since by including the day will make the visulization too conmplex and I still need to learn more to build an interactive visualization to include more details. The data was collected by the sensors that were set in the only bicycle routes. It includes bicycles and other micromobility devices including e-bikes, scooters, and e-scooters. But for the riders on the sidewalk, in motor-vehicle lanes, or in painted buffer zones were excluded. Many detectors were not active from 2019 to 2022 and have since been replaced. Since 2022, sensors have been calibrated based on manual counts. Checks are done periodically to verify calibration. Data from older detectors that have since been replaced have been validated using historic data where available. That are the "UNderwater labour" behind the dataset.

 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
