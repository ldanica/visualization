# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

For this assignment, I used the dataset "Ontario top baby names (female)" from Ontario's Open Data Catalogue: https://data.ontario.ca/dataset/ontario-top-baby-names-female.

Here is the visualization:
![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/danicaleung/DSI_Repo_Assignments/visualization/02_activities/assignments/assignment_4_python_visualization.png?version%3D1733114432079)


    > What software did you use to create your data visualization?
    I used the Matplotlib library in Python to create this visualization. The code was written and tested using VS Code.

    > Who is your intended audience? 
    The intended audience is for anyone who is interested in knowing what the most popular female names were for the last 110 years or so. I believe expectant parents would have more interest in this than most people.
    
    > What information or message are you trying to convey with your visualization? 
    In this visualization, I'm trying to show the most popular female name for babies in Ontario for each year that data was collected. This spans from the year 1913 to 2022.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    This was a large dataset with over 91,000 entries. To plot all the data points, the resulting visualization would have been very cluttered, difficult to read, and difficult to interpret. I decided it would be best to plot only the most popular names. I also wanted to see the trends over time and since we had so many years of data, I thought it would be best to plot every single year. This left me with 110 data points to plot, which is more manageable but still contained a lot of information. In terms of asethetics and perception, I tried to keep the visualization clean. The title and axis labels give a clear indication of what information is being shown. With 110 bars to plot, it's easy for things to look messy so I added more tick marks on the y-axis and labelled each bar with the name to increase interpretability. I think this was a good compromise of accurately presenting the data without excluding too many data points.  
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    By using python coding, my visualization is very reproducible. The data was directly imported into VS Code without being altered and every step I took to explore the data is documented in my lines of code.
    
    > How did you ensure that your data visualization is accessible? 
    To ensure my visualization is accessible, I tried to keep everything simple and clean. It starts with using a style that is accessible to people with colour-blindness (tableau-colorblind10). Because of the amount of data points, I made the figure large to spread things out. I set all the labels to a larger font size as well as bolding the title and axis labels. 
    
    > Who are the individuals and communities who might be impacted by your visualization? 
    This visualization can impact anyone. I think it's an interesting visualization to learn a fun fact. For parents that are expecting a baby, perhaps they can use this visualization to pick a name for their own baby. Depending on their preference, they could use it to avoid these names or to find a popular name that hasn't been used in decades. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    The dataset is quite simple with only 4 columns and right away I wanted to exclude the ID column. It acted as an index, which pandas would have assigned an index column anyway so I decided to drop the column. Because of the amount of data points, I felt it was best to concentrate on the names with the highest frequency. There are only so many names with high frequencies and I felt that was more informative to the audience. If I were to look into the least frequently used names per year, there would be too many names with the same amount of frequency. I wanted to show the trends over all the years and with so many duplicates, it would have been too overwhelming of a visualization. This is why I chose to show only the top name per year.  

    > What ‘underwater labour’ contributed to your final data visualization product?
    The underwater labour that contributed to this data being collected includes the person who completed the paperwork to register their child's birth. This also includes the nurses that ensure the paperwork is given to the parent(s). From all the paperwork, there are the people who inputted this information into the birth registry and the IT staff that maintains the servers that host all this data. From my end, the labour includes cleaning and preprocessing the dataset, exploring the data, and familiarizing myself with matplotlib and python to create a visualization. I had to decide how to group and sort the data to convey the message I wanted through my visualizaion. I also tested different customizations to make the data more readable and accessible.


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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
