This project was very exciting for me, I learned so much along the way. I have been working with two web developers on creating an app that helps users find nearby 
medical marijuana dispensaries and recommends strains based on medical ailments. My task at this stage of the project has been collecting and cleaning data. 
There is a Kaggle dataset which lists a couple thousand strains along with a description, user rating, the medical effects they treat, and other effects they have.
However, we wanted to add much more data, including more stains, information about the lineage, updated user feelings, user reviews, and their terpene profile.
To create this, I worked on webscraping Leafly, a popular medical marijuana information website. For this project, I taught myself how to webscrape using BeautifulSoup 
and Selenium. I ended up being very successful, capturing all the information we wanted as well as some extra info. You can find this work in the leafly_scraper notebook. 
I began by collecting all of the strain names on their website, then visited each one individually. I used Selenium to click on each strain, click through pop-ups and age gates,
and to click to load all reviews. From there I was able to create a dataset of all the feelings the users reported, THC content, the star rating, any images available,
parents and children of the strain, and the level of various terpenes in the strain. 

The other files were collected from an API that updated the above mentioned Kaggle dataset, and another API called Otreeba. The other notebooks clean the incoming leafly data
before merging it with the other files. In the last cell of the last cleaning notebook, I filter a dataset of 10,000 strains down to about 3,000 which contain the most
information about their strains. This created valuable, clean, and informative data that the web side is using to create a beautiful app. I have assisted them with crafting
the associated graphs in JavaScript. 

Through this project I learned HTML backwards and forward, BeautifulSoup and Selenium, and how to navigate CSS and JS features such as lazy loading. It was very valuable,
not to mention enjoyable, to learn so much by simply applying myself and learning anything I needed to solve the problem. 
