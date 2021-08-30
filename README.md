# Mission-to-Mars

## Purpose
The purpose of this challenge was to use HTML and Python to scrape websites for data about Mars, then create a web app to display and scrape the results. 

## Results
### Deliverable 1: Scrape High-Resolution Mars Hemisphere Images and Titles
After directing the web scraper to the Mars hemispheres url and creating a list of all of the four hemispheres, I created a loop to collect the titles of each hemisphere and their respective images. The image urls are also saved. 

<img width="469" alt="Screen Shot 2021-08-29 at 9 15 26 PM" src="https://user-images.githubusercontent.com/85946042/131282198-e789377a-95ab-48ba-b4f3-d1892b7d548d.png">

### Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles
In the index.html file, the hemisphere thumbnails and their titles are displayed at the end of the webpage. 
<img width="968" alt="Screen Shot 2021-08-29 at 9 41 16 PM" src="https://user-images.githubusercontent.com/85946042/131282204-29e8ba63-4bc9-4d26-a2cb-85f7042aab82.png">

### Deliverable 3: Add Bootstrap 3 Components
The resulting web application displays clearly on both a desktop browser and a mobile device. 
This code block ensures that the page renders in a mobile format and allows zooming capabilities. 

 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    
I added additional Bootstrap 3 components to style the webpage to create a unique experience. First, I changed the background colors of the body (light cyan #E0FFFF) and the title container (cadet blue) to make the webpage pop with visually appealing colors. Next, I changed the color of the web scraping button to green to make the button fit the color scheme (and, in HTML, a green button is a 'successful' button, so I decided that the web scraping button should be labeled as such in the code block, since it is successful at scraping data!). 

<img width="464" alt="Screen Shot 2021-08-29 at 9 43 20 PM" src="https://user-images.githubusercontent.com/85946042/131282218-abc1e2ca-527b-4db9-bae2-4f3a6c7a9061.png">


<img width="1424" alt="Screen Shot 2021-08-29 at 10 40 53 PM" src="https://user-images.githubusercontent.com/85946042/131282227-e28aff5d-6590-4f44-ae13-d1a0d00388cd.png">
## Summary
At the end of the challenge, I was able to successfully scrape NASA websites to collect and save information about Mars, and display it on a webpage using HTML formatting. By using Bootstrap 3 modifications, I was also able to customize my webpage to make the data visually appealing!
