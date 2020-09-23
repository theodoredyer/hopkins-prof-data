#### The goal of this project is to build a tool to help me analyze data from Hopkins professor student evaluations in order to select the best professor for upcoming classes by comparing them to eachother in a set of criteria that I have not yet determined. 

### How to Use
- To see the work I've done so far, open datawork.ipynb. This is a work in progress and currently I'm only using it to evaluate professors for one particular course.

### Steps
- 1 Scrape data from https://ep.jhu.edu/course-evaluation-results-public-reports
- 2 Compile data into a spreadsheet
- 3 Use python and data analytics tools to break this data up into separate csv files.
- 4 Determine how to structure my csv files, all professors for a class in a specific file? or all professors separated? etc
- 5 Determine important comparison criteria for professors (Time spent per week per class, some composite score based on the data)
- 6 Construct composite scores and modify data frames to include these
- 7 Perform basic data visualization in python in a jupyter notebook (Using Seaborn/matplotlib/pandas built in)
- 8 After determining the best visualization methods, build them in d3 to host on my project website.

### Done
- Determined the composite scores I want to calculate for each course

### Updated steps
- Calculate composite scores for each data field (CCR/GCR/ICR, etc.) and add new dataframe columns using pandas.

### Challenges
- Determining how to obtain the data from the site (the only possible way I can see at the moment is manual, considering I need to download pdfs which include the data, but they are text based so maybe there is a solution, going to research)
- Determining a valuable composite teacher score based on criteria that are important to me

### Extra Features
- Build a machine learning model to select professors for me. I'm imagining a way to do this would be supervised learning with data (professor x, professor y) as input, and my decision. Some iterative approach would be needed in this approach to compare all professors for a given course to arrive at a winner. Would likely use brain.js and integrate this into the project section of my personal site.

## Goal
- Build this tool and use it to gain insight towards making smart choices when selecting professors for my upcoming semesters.
- Get more experience in data analysis

## Goal++
- Implement a ML model to select my professors
