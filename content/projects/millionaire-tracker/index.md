---
title: "Millionaire Tracker"
date: 2024-12-31
draft: false
project_tags: ["millionaire-tracker", "joseph-murray", "influencer"]
status: "evergreen"
weight: 2
summary: "Golang web app to display the #millionaireinthemaking progress"
links:
    another_link:
        text: "GitHub Repository"
        icon: "fab alt brands fa-github"
        href: "https://github.com/epchao/millionaire-tracker"
        weight: 2
---

[@thejosephmurray](https://www.youtube.com/@thejosephmurray) has been tracking his daily income and expenditures for almost a year now and I wanted to visualize that progress through a graphical dashboard and perform an analysis to see how long it'll take for them to become a millionaire using solely profit and loss statements!

View the **README in the GitHub repository link** to view the system design, usage, and development steps.

# Tools
* GORM - Model the shorts data
* GoCV & TesseractOCR - Extract last frame from shorts and retrieve expense & income data 
* GoFiber - Create web app to display analytics dashboard
* CRON - schedule task of searching the millionaire-tracker videos and finding the expense and income data
* PostgreSQL - database for storing the relevant information