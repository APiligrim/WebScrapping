# WebScrapping Indeed with BeautifulSoup

Project's Main Idea: Web Scrape the website Indeed.com with BeautifulSoup to see internship openings for open Software Engineering positions and spot trends for:

        - programming skills (languages, frameworks, types of experiences) that are most in demand 
        - locations of different job openings
        - compare how salary for SE interns (if available) is different across different states 
        - does company rating affect salary
 
 
#### Packages that need to be installed to run the python files 
I used anaconda navigator:

1. conda install -c conda-forge google-api-python-client
2. conda install -c conda-forge wordcloud
3. conda install -c plotly plotly 
4. conda install -c conda-forge geojson
5. conda install -c conda-forge googlemaps
5. conda install -c conda-forge folium

### Final Plots from Data Visualization

#### Plot 1: Top Keywords in the Describtion section 
![](finalplots/plot1.png)
#### Map 1: Locations of job opeinings in the dataset 

![Alt Text](https://media.giphy.com/media/dYxgSCNKSqP0Jlmy3k/giphy.gif)
#### Map 2: Locations with higher salaries displayed by circle sizes
![Alt Text](https://media.giphy.com/media/eHRmiDNCaPxqLjLxr9/giphy.gif)
#### Plot 2: Correlation between Salary and Rating 
![](finalplots/salary_company.png)
#### Plot 3: Top requirements for Software Engineering Interns displayed by frequent keywords 
![](finalplots/plot2.png)
#### Plot 4: Top requirements for Software Engineering Interns (in a bar chart) 
![](finalplots/plot5.png)
