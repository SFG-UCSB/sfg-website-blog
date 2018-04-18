+++
title = "Building a Blog with Blogdown and GitHub"
date = "2017-01-23"
tags = ["R", "blogdown", "GitHub"]
categories = ["Basic R"]
banner = "img/banners/banner-4.jpg"
tbanner = ""
authors = ["Tyler Clavelle"]
menu = "https://www.tylerclavelle.com/code/2017/blogdown/"
+++

When I first started learning to code in R, Google was (and still is) my go-to when I had a question. It didn’t take long to realize that this generally brought me to one of two destinations - StackOverflow or [Insert Name]’s blog. So, I created a StackOverflow account and decided to start my own data science blog. However, I didn’t quite know where to start and spent most of 2016 scoping different platforms. While I won’t go into all the details of this process, I ended up with blogdown. blogdown is a R package that combines the ease of RMarkdown with the flexibility and customizability of Hugo. Hugo is an open-source static site generator similar to Jekyll, which means it builds your website once rather than each time a user visits it by taking all files within the website’s directory and rendering a complete website.