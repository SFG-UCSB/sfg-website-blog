+++
title = "Using R to extract data from web APIs"
date = "2017-06-05"
tags = ["R", "API", "httr", "jsonlite"]
categories = ["Basic R"]
banner = "img/blog/extracting-data-APIs.jpg"
tbanner = ""
authors = ["Tyler Clavelle"]
menu = "https://www.tylerclavelle.com/code/2017/randapis/"
+++

We all know the feeling; You find the perfect data set only to discover it’s held hostage in 30 pages of a PDF formatted by a drunk toddler or in 467.5 Excel worksheets spread across 19 workbooks emailed to you by a guy named Melvin. If you’re lucky, maybe there’s an online data platform where you can query some mythical database and download individual data files… One. At. A. Time. In a perfect world, however, all the data you’re nerdy heart could desire is freely accessible via an Application Programming Interface (API). This tutorial will walk through the basics of using the R language to obtain data from a web API. I will explain the basic concepts and demonstrate getting data from a handful of publicly accessible web APIs.