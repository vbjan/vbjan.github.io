---
layout: default
---

# Webscraping Bot for Automating Gym Reservations

Covid brought restrictions on the amount of people allowed in the gym I usually go to with it. One had to reserve a slot via an online form. This begged for automation for any regular gym-goers. So I implemented a webscraping bot that does the reservation automatically at the times I wanted it to over the course of a week, as specified in a txt-file.

I chose the selenium framework to implement the bot and hosted it on an AWS-server to ensure it could run independently of my everyday laptop. The execution of the script is triggered with crontab.

[[GITHUB REPO]](https://github.com/vbjan/ASVZ_bot)

___

[< back](../index.html)
