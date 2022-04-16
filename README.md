# Python Live Project

## Introduction

  Over the course of 2 weeks I had an awesome opportunity to work with a group developing a full scale MVT application using the Django framework in Python. We were given the task to build on and expand a pre-existing application while focusing on my own individual stories. We used Microsoft's Azure DevOps for our project management, PyCharm for our IDE, and a virtual environment to maintain consistency with the already existing application. I used this opportunity to create a sub-application that displays a webpage with template inheritance, adding CRUD fuctionality, and the ability to access and display information from an external API. You can read in more detail below. 
  
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


## Reflection
