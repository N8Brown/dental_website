# Dental Website
A Django-based demo website for a fictional dental practice.

![Home page of a website](home-page.jpg)

## About
Templates play a big role in building websites and web applications with the Django framework. Being able to incorporate not only templates made from scratch but also third-party templates (both free or purchased) into a project is key to being a successful Django developer. 

This website was built as part of a course by John Elder on his [Codemy](https://codemy.com/) platform, which focuses on integrating static third-party HTML templates into a Django project to create dynamic, real-world websites. Other key takeaways from this project include sending email via Python and deploying a Django project to Heroku for live hosting.

This project uses the Dento template by [ColorLib](https://colorlib.com/), which has been refactored to include a `base.html` template and update all live `href` and `src` attributes to Django static and URL tags.

The `base.html` template holds the common components of the website, including the header, footer, and navigation, and is extended by all page templates. Using this approach versus simply updating the template with static and URL tags helped to reduce the overall size of the template files from 151kb down to 90kb. It also better aligns the website structure with the Django DRY (don't repeat yourself) design philosophy by utilizing template inheritance.  

While the tutorial course focused on using Heroku as the web hosting service, this particular demo site is hosted on DreamHost and required a slightly different deployment process.

## Meta
[Nathan Brown](https://www.nathanabrown.com) - [@_N8_Brown](https://twitter.com/_N8_Brown) - contact@nathanabrown.com 

Live Website: [https://www.dental.nathanabrown.com](https://www.dental.nathanabrown.com)

GitHub Repository: [https://github.com/N8Brown/dental_website](https://github.com/N8Brown/dental_website)
