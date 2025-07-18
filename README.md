# -CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS

COMPANY : CODTECH IT SOLUTIONS

NAME : R NAVYA

INTERN ID : CT08DN1419

DOMAIN : FULL STACK WEB DEVELOPMENT

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH



# Chrome Time Tracker Extension

This Chrome extension is designed to help users track the time they spend on different websites and gain insights into their productivity. 

It monitors browser tab activity and records time spent per site, then stores this data in a backend database (Node.js + MongoDB).

Sites are categorized as **productive** (e.g., GitHub, Stack Overflow) or **unproductive** (e.g., YouTube, Facebook) based on a predefined list.

## Features

- Tracks active tab usage and hostname
  
- Records time spent and categorizes websites
  
- Stores user activity in MongoDB using REST API

- Displays total, productive, and unproductive time in popup

- Provides backend routes to fetch and store data

- Simple and lightweight, privacy-conscious design

# Load Extension in Chrome

Go to chrome://extensions

Enable Developer mode

Click "Load unpacked"

Select the productivity-tracker folder


# How it works

When you open Chrome, the extension loads in the background via the background.js script defined in the manifest.json.

Every time you switch tabs, the extension,

Notes the hostname (e.g., github.com)

Records the time when you started using that tab

Calculates the time spent on the previous tab

When a user leaves a tab, the extension:

Calculates the duration spent on that site

Classifies the site as:

 Productive – like leetcode.com, github.com

 Unproductive – like youtube.com, facebook.com


 # Output
 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/633f6011-fe3b-49e3-9f6b-6298d8299421" />
