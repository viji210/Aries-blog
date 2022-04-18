# Aries-blog
    It was my first full fleged Blog website that is built with Flask framework as its backend, It as a beautiful frontend that is created by tinkering and changing a free template that was selected from the HTML5 website.

## Authentication
    Only authenticated users (i.e, users who are created an account and loggged in) can comment on blog posts.

## Authorisation
    Only authorised users (i.e, users recognised as admin) can create, update, or delete blog posts, it was inbulit in Django but since I used flask I have to create it from scartch.

## Relational Database
    Has a Postgresql as its Database, Its consists of three tables related to each other, Users table contains info about users, Blog table Contains info about the blog posts and has a one to many relationship with Users as it parent, so on deleting a User the blog posts related to them gets automatically deleted, Comments table contains info about the comments made by the users it maintains a on to many relationship with the Users and Blog table both as its parents so if a user get deleted all the comment made by them also gets erased and if a blog post gets deleted all the comments in the blog post also gets deleted with it.

## Contact Form
    It has a contact form in it which uses SMTPlib to send a email to myself with all the details that you have been entered in the form

## Depolyed on Heroku
    this fully functional website is deployed and running on heroku here is the link to it https://aries-blog.herokuapp.com/
