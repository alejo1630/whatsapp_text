# Whatsapp Chat Text Analysis

This Python Notebook creates word clouds using text information from the two users whatsapp chat.

## 🔰 How does it work?

- The chat text is downloaded from whatsapp using the "Export Chat" option and selecting "Download Without Media".

<img src = "https://github.com/alejo1630/whatsapp_text/blob/main/Images_Readme/1.png" width="400" >


- The information uploaded from the .txt file must be modified in order to get only the users data and their chats.

  - Drop the rows with line breaks
  - Split columns
  - Drop columns with URL data
  - Remove time information
  - Remove rows with the mesagge "Media omitted"
 
 <img src = "https://github.com/alejo1630/whatsapp_text/blob/main/Images_Readme/2.png" width="400" >

- Three .txt files are created
  - Text information for both users
  - Text information for User 1
  - Text information for User 2
- A list of stop words is uploaded. In this case, using the spanish language.
- The word clouds are created using [StyleCloud](https://towardsdatascience.com/generate-modern-stylish-wordcloud-with-stylecloud-9cbb059696d2) library
  - Both users
   <img src = "https://github.com/alejo1630/whatsapp_text/blob/main/Images_Readme/both.png" width="300" >
   
  - User 1
   <img src = "https://github.com/alejo1630/whatsapp_text/blob/main/Images_Readme/u1.png" width="300" >
   
  - User 2
   <img src = "https://github.com/alejo1630/whatsapp_text/blob/main/Images_Readme/u2.png" width="300" >

- Word Cloud Icon can be changed using the list available at [W3 Schools Website](https://www.w3schools.com/icons/default.asp)

## 🔶 What is next?
- Text analysis for Groups and Communities
