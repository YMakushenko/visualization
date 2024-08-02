# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    1. I used Jupyter Notebook for creating my data visualization. Specifically, I used Python libraries including pandas for data manipulation, folium for creating interactive maps, and geopy for geocoding addresses.

    2. I used Power BI to create my second data visualization.


    > Who is your intended audience? 
    1. The intended audience for this visualization includes parents looking for licensed child care centers in Toronto, policymakers, and researchers interested in analyzing the distribution and availability of child care services in the city.

    2. The intended audience for this visualization includes policymakers, city planners, education administrators, and parents in Toronto. This visualization is designed to help them understand the distribution and capacity of licensed child care centres across the city.

    
    > What information or message are you trying to convey with your visualization? 
    1. The main message of the visualization is to show the geographical distribution of licensed child care centers in Toronto and to highlight which centers offer fee subsidy contracts. This helps in identifying areas with high or low availability of subsidized child care services.

    2. The visualization aims to convey the total number of child care spaces available in various licensed child care centres in Toronto. It highlights the different types of child care spaces (e.g., infant, toddler, preschool, kindergarten, school-age) and distinguishes centres that offer fee subsidies from those that don't.

    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    1. Substantive: The map is focused on providing meaningful information about the location and subsidy status of child care centers. This helps users make informed decisions.
    Perceptual: Different colors are used to distinguish between centers that offer fee subsidies and those that do not, making it easy to perceive the information at a glance.
    Aesthetic: The map is designed to be visually appealing yet simple. Clean markers and no legends by default ensures that the map is not cluttered. Legends pop-up when to move the cursor over the selected marker. Markers are chosen to be easily visible against the map background. The map is centered around Toronto with an appropriate zoom level to give a clear view of the city and the distribution of the centers.

    2. Substantive: I ensured the data accurately represented the number and types of child care spaces available at each centre.
    Perceptual: I used different colors for the different types of spaces (IGSPACE, TGSPACE, PGSPACE, KGSPACE, SGSPACE).
    Aesthetic: I chose a clean and readable layout, with a horizontal bar chart to make it easy to compare the total spaces across different centres. The use of color helps in distinguishing between the various categories.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    1. I ensured reproducibility by:
    - using a publicly available dataset from the City of Toronto’s Open Data Portal.
    - writing and documenting the code in Jupyter Notebook, which can be shared and executed in any environment with the required libraries installed.
    - including installation commands for necessary libraries to facilitate setting up the environment.
    If the tool was not reproducible, it would significantly impact the usability and reliability of the visualization, making it difficult for others to verify or build upon my work.

    2. To ensure reproducibility, I used Power BI, which allows for the visualization to be recreated using the same dataset and steps. If Power BI weren't reproducible, it'd impact the ability to verify and build upon the analysis.

    
    > How did you ensure that your data visualization is accessible? 
    1. Using clear and distinguishable colors for markers to aid in quick identification.
    Adding tooltips and pop-ups on the map markers to provide additional information about each child care center.
    Ensuring the map is interactive and can be zoomed and panned for better visibility and user experience.

    2. I used apropriate colors and included labels and a legend to ensure the visualization is accessible to people with visual impairments. The chart is designed to be clear and easy to interpret, with explanatory text for different space types and subsidy status. 
    
    > Who are the individuals and communities who might be impacted by your visualization? 
    1. The individuals and communities impacted by this visualization are:
    - parents looking for child care options in Toronto
    - policymakers and local government officials who plan and allocate resources for child care services
    - community organizations that advocate for improved child care services and accessibility

    2. The individuals and communities impacted by this visualization are:
    - parents looking for child care
    - policymakers making decisions about funding and resource allocation
    - and child care providers looking to understand the competitive landscape

    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    1. I included features that are most relevant to the intended audience:
    - the address and name of the child care centers to identify their locations.
    - the subsidy column to highlight centers that offer fee subsidies.
    - geographic coordinates for plotting on the map.
    Other features, such as the total number of spaces available and building types, were not included in the map but could be used in additional visualizations if needed.


    2. I included features directly related to the capacity and subsidy status of the child care centres, as these are the most relevant to the intended audience. Features such as the exact address and phone numbers were excluded to maintain focus on the capacity and subsidy information.

    
    > What ‘underwater labour’ contributed to your final data visualization product?
    1. The ‘underwater labour’ contributed:
    - cleaning and preprocessing the data, including handling missing values and ensuring data quality.
    - geocoding the addresses to obtain latitude and longitude coordinates, which was a time-consuming process.
    - designing the visualization to be both informative and visually appealing, which included choosing appropriate colors and ensuring the map's interactivity.
    - testing and debugging the code to ensure it runs smoothly and accurately represents the data.

    2. The ‘underwater labour’ included cleaning the data, ensuring its accuracy, and deciding how to best represent it visually. This also involved trial and error in Power BI to find the most effective chart type and design for conveying the information clearly and effectively.


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
