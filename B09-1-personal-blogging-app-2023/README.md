# SMIT Batch 9 Mini Hackathon 2023

## Personal Blogging App

## [Figma link](https://www.figma.com/file/57xYjZYhVpCQAALtxPH3kO/SMIT-Mini-Hackathon-Task---personal-blogging-app?type=design&node-id=4291%3A2280&mode=design&t=pdxImmaF1j7mrVCF-1)

## [Completed By Abdul Ahad](https://github.com/ahadsts9901)

## [Github Repository](https://github.com/ahadsts9901/smit-b9-mini-hackathon)
## [Live Hosting](https://ahadsts9901.github.io/smit-b9-mini-hackathon/)

## Rules

- You can use Internet, books and other resources such as your boilerplate code, however you are not supposed to talk or ask help from other participants of hackathon. SMIT management hold authority to qualify you from hackathon if you violate.
- You will start your hackathon by creating a private repository on Github and you must keep it private until submission time ends.
- Submission will be your github repository url and a public hosting url that can be visited over internet, if you do not push your code on github repository or if you failed to host your website on internet your submission will not be acceptable.

## Abstract

This design document is created using bootstrap 5 components, how ever you are free to use other css library/framework or plain css if you want, you are not restricted to make as it is design you are free to use different color and modify components as soon as functionalities are intact and requirements are fulfilled.

## Signup page

- Signup page must have to have email and password signup option you can use firebase authentication however you are free to use other authentication options if you want.
- First and last name is required, first name should be atleast 3 characters and last name should be atleast 1 character, firstname and last name field should not exceed 20 characters, enforced through html5 validation.
- Email field is required and must includes @ enforced through html5 validation.
- Password field is required and must have to have atleast 8 characters and must include capital and small later characters, enforced through html5 validation.
- Signup Form should not submit if user enter different password in repeat password field.

## Login page

- Login should have HTML5 validation for email
- After a successful login it should automatically redirected to dashboard page
- If a user try to open login page when it is already logged in it should automatically redirect to dashboard and should not stay on login page.

## Dashboard Page

- On dashboard page there should be an option to post a new blog, a blog must have a blog title and body text input.
- Blog title must be between 5 to 50 characters, and body text must be between 100 to 3000 character. enforced through html5 validation. validation through firebase rules would be a plus but it is not required.
- Dashboard page must display all previously posted blogs of logged in user sorted by date (latest on top). each post should display with publish date.
- User should be able to update the title and body of article.
- When user click on delete button it must confirm delete to avoid accidental deletion of blog post.
- Dashboard must show logged in user full name and a logout button.

## Profile Page

- Logged in user should be able to access profile page by clicking on his on his name top right corner of the screen.
- On login page user should be able to update profile photo, first name, last name and password.

## What a user can do without Login

- If user is not logged in and open website home page user should see all blogs from all users sorted with date (latest first). each blog displayed must contain blog title, author name, date published, blog text and a button to see all blogs from that author.
- On any blog, user must be able to click on “see all blogs from this author” and presented with all blogs only from that user with profile picture, name and email as shown in design, and an option to go back.
- Continuously show login button on top of the screen when not logged in.
- This page will greet user depending on user local time, greeting would be either good morning, good noon, good evening or good night.
