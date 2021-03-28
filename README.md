# tech-blog
## Table of Contents

* [Description](#Description)
* [Installation](#Installation)
* [Screenshots](#Screenshots)
* [License](#License)



# Description
The aim of this application is to build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well.

This application runs on Heroku. 

# Installation 

You use the deployed application [here](https://tech-blog-olivia-owen.herokuapp.com/login)

In order to use this application you will need to open the deployed application on Heroku.

From here you will either be able to log in, or sign up if you dont already have an account.

You will then be able to write a blog post after you sign up, or if you log in you will be taken to your dashboard, where you can either write a new post of see the posts you have already made.
You can also click edit where you will be able to edit your post, or delete which will remove your post.

 
# Screenshots


The screenshots below show the following:

The log in page
![get all tags](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/GET%20ALL%20TAGS.png)


You can also see your previous posts or write a new one.:

![get tags by id](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/GET%20ALL%20TAGS%20BY%20ID.png)


You can also create a tag using a POST request as you will see below:

![create tag](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/CREATE%20TAG.png)


And this is then reflected when you send a new GET request for "Get All Tags":

![updated all 1](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDTED%20GET%20ALL%20TAGS%201.png)


This can then be updated using a PUT request, in order to do this, you will need to enter the ID number you wish to update in the URL location, as below:


![update request](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDATE%20TAG.png)


This will then again reflect when you send a new GET request for "Get All Tags":


![updated get all](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDATED%20GET%20ALL%20TAGS%202.png)


You can also delete a request, which again will require you to enter the ID you wish to delete into the URL and click send:


![delete request](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/DELETE%20TAG.png)


As you can see below, this will then ammend and update on the next GET request for "Get All Tags"


![final get all request](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDATED%20GET%20ALL%20TAGS%203.png)









# License
![license: MIT](https://img.shields.io/badge/License-MIT-blue.svg)