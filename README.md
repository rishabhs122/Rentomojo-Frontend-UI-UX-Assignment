# Rentomojo-Frontend-UI-UX-Assignment

Using the following mock APIs, create a blog frontend using a framework of your choice
(Angular, React, Vue).
API DETAILS:
Host: https://jsonplaceholder.typicode.com
GET /users
GET /posts/1
GET /posts/1/comments
GET /comments?postId=1
GET /posts?userId=1&skip=0&limit=10
DELETE /posts/1
TASK DETAILS:
Home page: A simple table to display users, with columns as name, company, blog posts.
Using the /users API, fill up the name and company name of each user along with a link to
the Posts page of that particular user. It should have a filter for user name and company
name.
Posts page: This page url will take a parameterised userId and will display the list of posts
(use the post title) of that particular user. Each of these will have a link to the Post Details
Page. Use pagination with skip, limit params in the API. It should have a filter for post title
text matching.
Post Details Page: Use URL parameters to get the post ID and fetch the details accordingly
with respective API. Display both title and body. It should also have a filter for text matching
in title as well as body. There will also be a link Comments. Clicking on the comments link
will fetch the comments and show them on this page itself. Also there will be a delete button
on this page which will delete the post calling the respective api. After a successful response
from delete API, it will redirect to the Posts page of the respective user again.
You would be assessed on the following criteria:
● Completeness of all functionalities along with efficient code structuring and naming
practices
● Design and styling practises, along with responsiveness across devices
● Use of a central store management mechanism is encouraged
● Proper error handling and interaction with the user using loaders, etc.
● The use of a CSS preprocessor would be appreciated
For some extra brownie points:
● The use of sprites instead of many large images
● Implementation of a dark theme (alternate color combination profiles) ● Option of
switching between design layouts in the home screen (listing, cards, expansive panels, etc.
