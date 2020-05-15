---
layout: project
type: project
image: images/cram-connect/connect-project.jpg
title: Cram Connect
permalink: projects/cram-connect
# All dates must be YYYY-MM-DD format!
date: 2020-05-15
labels:
  - Web Application
  - Meteor
  - Semantic React
  - ICS314

summary: Developed the Cram Connect website to enable UH Manoa students to find their best fit study spot on or around campus! Used issue driven project management, as a team of 4, to develop the Cram Connect web application. Implemented Cram Connect using Meteor and React.
---

<img class="ui large centered rounded image" src="../images/cram-connect/connect-landing.jpg">

## Application Overview
Cram Connect Github Organizational Page:
[https://cram-connect.github.io/](https://cram-connect.github.io/)

## Matt's Development Contributions

In our Cram Connect development, I feel that one of my biggest contributions to our project was setting up the data model. Our data model was designed in the same way as [Bowfolios data model](https://bowfolios.github.io/#data-model). Essentially, the default information for our system was based on Users and Locations and their associated individual data. We then fed this data into our system and stored it as follows. You can think of the combined collections of data, including *ProfileQualities*, *ProfileLocations*, and *LocationQualities*, as associative links between *Profile*, *Location*, and *Qualities* collections stored on the server.

Below is a diagram of the data model that I implemented for Cram Connect. Although it may seem easy to use the same general model pattern as Bowfolios, it took a lot of time to truly understand how this particular type of data model was implmented. Likewise, it took a lot of time to implement this into our system. However, I believe this made our data manipulation process much easier in the end.
<img class="ui medium right floated rounded image" src="../images/cram-connect/connect-dataModel.jpg">

Using this data model, I was able to implement an Edit Profile page, which would use our new data model and allow the user to input information. The Preferences (associated qualities) and Favorite Spots (associated locations) allow the user to pick from a MultiSelect dropdown to choose their preferences. In addition, I used Sweet Alert to aid in the process and confirmation of new profile image URLs.
<img class="ui large centered rounded image" src="../images/cram-connect/connect-editProfile.jpg">

I later took on the responsiblity of fixing the favorites page.
<img class="ui large centered rounded image" src="../images/cram-connect/connect-favorites.jpg">

As another team member was unable to complete the search page, due to covid19 and family related measures, I worked with Willy to complete the base functionality and appearance of the search page. Personally, I was able to debug code and speed up the process by quickly identifying problemantic spots, and I then clearly communicated the specific issues to my group. For instance, we were passing in *location* to a Card.Group component, which would help us to show all of the cards. However, I later was able to understand that **location** is a predefined property and passes intrinsic data, including *pathname, search, hash, and state*. Below, you can take a look at the fruits of our labor.
<img class="ui large centered rounded image" src="../images/cram-connect/connect-search.jpg">

Willy implemented the individual location page himself. I thought he did a really good job, so I wanted to share that here, too.
<img class="ui large centered rounded image" src="../images/cram-connect/connect-location.jpg">

also loaded the assets file/conditions

## Lessons Learned

- teamwork
- efficient use of project board
- make issues smaller
- split work up and make sure overlapping parts are covered
