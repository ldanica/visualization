# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify:

For this assignment, I used the dataset "Ontario top baby names (female)" from Ontario's Open Data Catalogue: https://data.ontario.ca/dataset/ontario-top-baby-names-female.

Here is the visualization:
https://public.tableau.com/app/profile/danica.leung/viz/Ontariotopbabynamesfemale/Dashboard1#1

![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/danicaleung/DSI_Repo_Assignments/visualization/02_activities/assignments/assignment_4_tableau_visualization.png?version%3D1733124398071)
    
    
    > What software did you use to create your data visualization?
    I used Tableau Public to create this visualization. I used Python and VS Code to process and sort the original dataset to the parameters I wanted. I exported a new csv file, uploaded it to Tableau, and created this graph. 

    > Who is your intended audience?
    The intended audience is for anyone looking for a quick visual of the most common female names in Ontario in the last 110 years or so.  
    
    > What information or message are you trying to convey with your visualization?
    In this visualization, I'm trying to show the top 20 female names for babies in Ontario spanning from 1913 to 2022.  
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Having already created a comprehensive graph using Python, I thought it would be best to give a quick and easy visualization using Tableau. Since I narrowed down the dataset to 20 names, I made a word bubble graph to make the data aesthetically pleasing, clean, and easy to interpret. It may not be substantive considering how much information was in the original dataset, but it provides the audience with quick information.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    To ensure reproducibility, I used python coding to sort the dataset by the most frequently used names. I created a new dataframe and exported it as a csv file, which was then uploaded to Tableau as the source data. By following the code, you should be able to recreate the data from the csv file (which is found under the sheet tab in Tableau) and then reproduce the visualization.
    
    > How did you ensure that your data visualization is accessible?
    To make it accessible, I chose a colour scheme that is easier to read by people with colour-blindness. I kept the labels in each bubble simple by only including the name and the year it was the most popular. The title of the visualization describes the exact message I'm trying to convey. Also, the size of the bubbles tell you how frequent a name was used compared to others without you needing to hover over each mark to see the frequency.
    
    > Who are the individuals and communities who might be impacted by your visualization? 
    This visualization can impact anyone. I think it's a visualization that teaches the audience another fun fact about names especially if they know someone personally with one the names shown. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Since I had done a visualization already showing the top names per year, I decided to go in a different direction using Tableau. Because the dataset is based on the frequency of words used, my first thought was to make a word cloud. I know it can be done using Python, but since I was using a new tool with lots of customization options, I decided to try it with Tableau. I originally had planned to layer 3 different datasets together based on different aggregations, but I couldn't familiarize myself quickly enough so I decided to keep it simple. I wanted to know through the 110 year span, which names were the most popular. For someone with a "unique" name like mine, it's something I'm interested in. From there, I simply sorted the data by frequency in descending order and filtered it to the top 20 names. I included the year on each marker as an extra interesting fact about when that name was the most popular. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    In addition to the underwater labour that contributed to the data being collected, stored, and uploaded, there was a big learning curve for me. I had never used any visualiation tools before other than Excel. Even then, creating graphs is not something I did regularly. I had ambitious plans to make a comprehensive, dynamic visual but learning how to use Tableau took longer than I anticipated.

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
