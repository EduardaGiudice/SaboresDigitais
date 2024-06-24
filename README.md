# Sabores Digitais

## 📑 Table of Content

* [Application Overview](https://github.com/EduardaGiudice/SaboresDigitais#-application-overview)
* [Challenge](https://github.com/EduardaGiudice/SaboresDigitais#-challenge)
* [Prioritized User Stories](https://github.com/EduardaGiudice/SaboresDigitais#-prioritized-user-stories)
* [Codes](https://github.com/EduardaGiudice/SaboresDigitais#-codes)
* [Technologies](https://github.com/EduardaGiudice/SaboresDigitais#-technologies)
* [Development](https://github.com/EduardaGiudice/SaboresDigitais#-development)

## Application Overview

### 📲 User Registration and Login

The user can create an account and log in to the application. All fields are validated using the Yup and React Hook Form libraries to allow only correct data to be entered by users. Authentication is done using JWT Token.

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/RegistroLogin.gif" width="250" height="550">

### 🍣 Recipe Feed

The "Recipe Feed" screen displays all recipes posted by all users. Each recipe is represented by a photo of the recipe, its name, a brief description, and the date it was posted. In addition, there are the "Like" buttons, which allow you to like the post if you liked it, and the "Comments" button, which opens a screen displaying all comments made on that specific post, also allowing you to add a new comment. Finally, there is the "View Recipe" button, which, when pressed, displays more information about the recipe, such as the ingredients and preparation method, for example.

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/Feed.gif" width="250" height="550">

### 🍦 New Post

The "New Post" screen allows the user to create a new recipe post. Here, the user can select an image of the recipe, choosing from the gallery or taking a photo with the device's camera. Then, they add the name of the recipe, a brief description and, finally, as many ingredients and preparation methods as desired. When the user presses the "Register" button, the post will be added to the "Recipe Feed".

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/NovoPost.gif" width="250" height="550">

### 🥣  My Posts

The "My Posts" screen displays all posts made by the logged-in user. There, by pressing the button with the edit icon, the user can edit all items in the post, including the image. There is also a button with the delete icon that, when pressed, displays a confirmation message. If the user confirms, the post is deleted from the database.

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/MeusPosts.gif" width="250" height="550">

### 🛒 Shopping list

On the "Shopping List" screen, the user can add as many items as they want. Simply select the button with the add icon, which will open a modal window where the user must enter the quantity of the item, then the unit of measurement of the item, and finally the name of the item. When pressing the "Register" button, the item will be listed in the shopping list. Each item contains a button with a delete symbol that, when pressed, allows the user to delete the specific item from the list. In the footer, we have the "Clear List" button. When pressed, a confirmation window will be displayed and, if the user confirms, the shopping list will be cleared and all items will be deleted.

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/Lista.gif" width="250" height="550">

### 🧑 Profile

On the "Profile" screen, we can view all the data of the logged-in user. There, the user can update the username and profile picture, if desired. The option to update the password is also offered. When pressing the "Update Password" button, a modal window opens where the user must enter the current password registered in the database, then select a new password within the validation rules and, finally, enter the new password again. If all the data is correct, pressing the "Update" button updates the password in the database.

In the upper right corner of the page, there is also the logout button. When pressed, the user is logged out of the application, returning to the login screen and leaving the JWT token as null.

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/Perfil.gif" width="250" height="550">

## 📌 Challenge

We live in a time of digital culture, which has revolutionized the way we do everything in our lives, from the way we work, study, entertain ourselves, and even the way we cook. While old recipe books, although valuable, face limitations in terms of storage and accessibility, digital technologies, especially mobile devices, offer new possibilities for interaction and sharing. The need arose to develop a solution that combines the richness of culinary traditions with the practicality and mobility provided by technology, overcoming the limitations of traditional means of accessing recipes. 


## 🏅 Prioritized User Stories

<img src="https://github.com/EduardaGiudice/SaboresDigitais/blob/main/docs/User%20Stories.png">

## 📃 Codes

* [Frontend Code access link](https://github.com/EduardaGiudice/SaboresDigitais-client)
* [Backend Code access link](https://github.com/EduardaGiudice/SaboresDigitais-api)

## 🛠 Technologies

The "MERN" development standard was used. The following technologies were used to build the mobile application:

<img src="https://img.shields.io/badge/Java%20Script-F7DF1E?style=for-the-badge&logo=JavaScript&labelColor=black">
<img src="https://img.shields.io/badge/MongoDB-%2347A248?style=for-the-badge&logo=MongoDB&labelColor=black">
<img src="https://img.shields.io/badge/Express-%23000000?style=for-the-badge&logo=express&labelColor=black">
<img src="https://img.shields.io/badge/React%20Native-%2361DAFB?style=for-the-badge&logo=React&labelColor=black">
<img src="https://img.shields.io/badge/NodeJS-%235FA04E?style=for-the-badge&logo=Node.js&labelColor=black">
<img src="https://img.shields.io/badge/Expo-%23000020?style=for-the-badge&logo=Expo&labelColor=black">
  
## 👨‍💻 Development

| Student              | GitHub Profile                                                              | LinkedIn Profile                                                                                         |
| ---------------------  | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |                               
| **Eduarda Giudice**           | [![](https://bit.ly/3f9Xo0P)](https://github.com/EduardaGiudice)    | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/eduarda-giudice/)     |
