# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  


# MY ANSWER
The dataset which I chose is "All sectors and seconded employees 2020" from [Ontario’s Open Data Catalogue](https://data.ontario.ca/)
It contains information on all public sector employees who were paid $100,000 or more in 2020 and are subject to the Public Sector Salary Disclosure Act.


# DATA VIS USING PYTHON

A separate jupyter file is attached for Python visualization, image is attached below as well

![alt text](<Python Visualization.png>)


- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I have used Python(matplotlib, seaborn) to create a box plot.

    > Who is your intended audience? 
    The intended audience for this visualization includes HR professionals, job seekers, and career counselors. This visualization can help them understand the salary distribution for different job titles, which can inform career decisions and salary negotiations.
    
    > What information or message are you trying to convey with your visualization?
    The visualization aims to show the distribution of salaries for different job titles (e.g., Professor, Manager, Director, etc.). The goal is to highlight the range of salaries within each job title, identify any outliers, and compare the median salaries across roles.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    Substantive: The visualization focuses on salary distribution, which is critical for understanding compensation variability within job titles.
    Perceptual: A box plot is used because it effectively shows the distribution, median, and outliers of salaries for each job title.
    Aesthetic: The chart is kept simple with clear labels and a consistent color scheme. Titles and axis labels are easy to read.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    The Python code used to generate the visualization is provided ina separate jupyter notebook. This ensures that anyone with the dataset and the code can reproduce the visualization. The code is well-commented and uses standard libraries (Matplotlib and Seaborn).
    
    > How did you ensure that your data visualization is accessible?
    The chart uses a color palette that is colorblind-friendly(Set-3).
    Axis labels and titles are clear and large enough to be easily readable.
    The chart is simple and avoids unnecessary elements that could confuse the audience.
    
    > Who are the individuals and communities who might be impacted by your visualization?
    Job Seekers: They can use this information to understand salary ranges for different job titles.
    HR Professionals: They can benchmark salaries and identify any discrepancies in compensation.
    Career Counselors: They can guide individuals based on salary expectations for different roles. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I have included Job Title and Salary to create the box plot and excluded Benefits and Sectors to keep the visualization focused on salary distribution by job title.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data cleaning: Checking for missing values, removing dollar signs and converting salary to numeric format.
    Filtering data to focus on the top 30 most common job titles for clarity.
    Customizing the chart in Seaborn to ensure it is clear and easy to interpret

# DATA VIS USING TABLEAU

Image: ![alt text](<Tableau Visualization.png>)

Link: https://public.tableau.com/app/profile/saleha.qureshi/viz/AverageSalarybySector2020/Sheet1


- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I have used Tableau Public to create a bar plot.

    > Who is your intended audience? 
    The intended audience for this visualization includes policymakers, HR professionals, and academic researchers who are interested in understanding salary trends across different sectors. This visualization can help them make informed decisions about resource allocation, salary benchmarking, and sector-specific workforce planning.
    
    > What information or message are you trying to convey with your visualization?
    The visualization aims to show the average salary across different sectors (e.g., Colleges, Hospitals, etc.) in 2020. The goal is to highlight which sectors offer higher average salaries and which sectors may need attention in terms of compensation.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    Substantive: The visualization focuses on the average salary, which is a key metric for understanding compensation trends.
    Perceptual: A bar chart is used because it is easy to compare values across categories (sectors). The y-axis represents salary, and the x-axis represents sectors.
    Aesthetic: Colors are used to differentiate sectors, and the chart is kept simple to avoid clutter. Titles and axis labels are clear and concise.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    Tableau Public is not inherently reproducible, however, I have customized the chart by adding titles, axis labels, tooltips, filters and adjusting the color scheme. I have also published the visualization to Tableau Public for sharing.
    
    > How did you ensure that your data visualization is accessible?
    The chart uses a color palette that is colorblind-friendly.
    Axis labels and titles are clear and large enough to be easily readable.
    The chart is simple and avoids unnecessary elements that could confuse the audience.
    
    > Who are the individuals and communities who might be impacted by your visualization?
    Employees: They can use this information to negotiate salaries or choose sectors with better compensation.
    Employers: They can benchmark their salaries against industry standards.
    Policymakers: They can identify sectors that may need intervention to improve compensation. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I have included Sector and Salary to calculate and visualize average salaries and excluded Benefits and Job Titles to keep the visualization focused on salary trends.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data cleaning: Checking for missing values, removing dollar signs and converting salary to numeric format.
    Grouping and aggregating data to calculate average salaries.
    Choosing an appropriate color palette and ensuring the chart is easy to interpret.


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
