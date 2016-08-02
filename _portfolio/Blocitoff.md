---
layout: post
title: Blocitoff
feature-img: "img/sample_feature_img_2.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030966/blocjams_1x.png"
short-description: Self-destructing to-do list application.      

---

Blocitoff is an application built with Ruby on Rails that allows users to create self-destructing to-do lists.

Blocitoff is a simple web application that allows the user to create a to-do list. Each item added to the list must be completed in 7 days. If the task is completed before then, the user can mark it as complete. Otherwise, Blocitoff will be automatically deleted.

User authentication is handled using the Devise gem. SendGrid was incorporated for teh application to email users and have them confirm their accounts. Bloccitoff was "Ajaxified" to improve the user experience of creating and destroying items on the to-do list. Automated Rake tasks were implemented to delete items after 7 days.

Blocmarks utilized the Devise gem to handle user authentication. Mailgun was incorporated into the application to handle outgoing emails for user registration and incoming emails to the user's account with the bookmarked URL. The Pundit gem was used to handle user authorization to ensure the user could only create and destroy their own bookmarks. 
