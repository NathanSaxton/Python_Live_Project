# Python Live Project

## Introduction

  Over the course of 2 weeks I had an awesome opportunity to work with a group developing a full scale MVT application using the Django framework in Python. We were given the task to select a theme and build on and expand a pre-existing application while focusing on my own individual stories. We used Microsoft's Azure DevOps for our project management, PyCharm for our IDE, and a virtual environment to maintain consistency with the already existing application. I used this opportunity to create a sub-application that displays a webpage with template inheritance, adding CRUD fuctionality, and the ability to access and display information from an external API. You can read in more detail below. 
  
## CRUD Fuctionality
  
  After setting up an object model using a relational database. I added some fuctions that could manipulate and call templates to view the items in the database. I started with using the ModelForm to create items for the database. Then using the Model manager I displayed all the items to be read using a template.

![image](https://user-images.githubusercontent.com/72226252/163694163-0d03f8a6-3188-49a8-904b-b9061c93f1b9.png)

  I then added the ability to read more details on the items in the database along with giving the user the option to update or delete the items. I also added an fuction to confirm to delete the item in the database before it was completely deleted. 

![image](https://user-images.githubusercontent.com/72226252/163694171-707ded97-45c7-418d-9f3b-b6fd18efbea0.png)

You can see in the Template and Front End Development section where I used the code above with templates to display the info for the user. 

## API 

 We were then given the chance to connect with an API that matches with the theme of our sub-application. I chose to use a RESTful API rather than the web scraping Beautiful Soup library. Taking advantage of the Request and JSON libraries, I was able to fetch data from the API which I was able to work with after parsing the JSON response. I was also able to take multiple lists of data and store them using the zip fuction which I used to display the content on the template. 
 
![image](https://user-images.githubusercontent.com/72226252/163694200-865d2232-9c07-4710-896d-4444c7a2ea14.png)

## Template and Front End Development

  Template inheritance was used for every page of my sub-application. I started by setting up my base template that I would use for everyone of my other templates, where I added linked to Bootstrap 4 and my own custom CSS file. I then made sure to include block tags and url tags when they were necessary. The example below is the template used to display the list of all the heroes currently in the database. (This can be seen in one of the images listed later in this section)

![image](https://user-images.githubusercontent.com/72226252/163700402-2ee392c4-efa5-4bf0-b801-f6c6b83dfdcc.png)

  I love a simple website nothing over complicated and something that gives a little more attention to detail. I chose this style because I thnk it looks nice, it's simple, and it doesn't crowd the webpage. The homepage I used the background image as the main 23focus, I titled it Batman's Black Book so it makes sense that it's main focus is the batman symbol. 
  
![image](https://user-images.githubusercontent.com/72226252/163699909-2ffc9106-831e-4ec1-868c-745bda7023ec.png)

I did my best to make the information easy to read while still matching the theme. I used basic tables to show the overview info without giving the full details on the items. Where I made the details page easy to read and edit if necessary as seen in the following 3 screenshots. 

![image](https://user-images.githubusercontent.com/72226252/163699992-2fd5e8e9-01bb-4581-98a8-67f8a1904c97.png)
![image](https://user-images.githubusercontent.com/72226252/163700064-fa2cbc51-af79-480e-b222-d8bb7f04010c.png)
![image](https://user-images.githubusercontent.com/72226252/163700103-5d600576-91f2-4077-be65-f3451e2a1ceb.png)

## Reflection

  This live project has been the best thing that's happened on my journey learning to code. I was able to work with other on the same project for the first time, learning how developers work on a single project. I got to work with our scrum master participating in daily stand-ups and project planning at the start. I'm finally able to see what it all looks like when everything is put together. Learning about API's, connecting to a database, and actually using that information to build a scalable site has been so fulfilling and I'm excited to continue learning and developing. 
