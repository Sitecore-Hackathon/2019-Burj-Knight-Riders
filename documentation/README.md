# Documentation

This Module is created during Sitecore Hackathon 2019.

## Summary

**Category:** Best enhancement to the Sitecore Admin (XP) UI for Content Editors & Marketers

## Problem: 
Marketer want to create a form and want to have an email sending functionality and track the lead of the website for their future interaction.
    -	But there is no option for Marketers to send EXM Mail without creating the contact in Sitecore, using Sitecore Forms.
<br><br>
## Solution:
We focused on both the above key problems where marketers can send email of there own choice based on the form behavior and in the background the form lead will be converted into the Sitecore contact, which marketer can further analyze in the experience profile.
<br><br>

## Pre-requisites

- Sitecore 9.1 With Xconnect

## Installation

Provide detailed instructions on how to install the module, and include screenshots where necessary.

* Use the Sitecore Installation wizard to install the [Create Profile and Trigger EXM Mail using Sitecore Forms](https://github.com/Sitecore-Hackathon/2019-Burj-Knight-Riders/blob/master/SitecorePackage/Create%20Profile%20and%20Trigger%20EXM%20Mail%20using%20Sitecore-0.1.zip)

## Configuration | Post Installation Steps

1)	Set Email SMTP for EXM if it is not configured.
    o	Or more details refer | Custom Email SMTP configuration: http://sitecoresolution.blogspot.com/2018/10/setup-your-first-email-with-sitecore-9-EXM.html

![Alt text](/Screenshots/Hackathon01.png?raw=true "Sitecore Hackathon")

<br><br>
2)	Create EXM Automated Email and provide all the details.
    o	And make sure you activate the EXM Mail.
![Alt text](/Screenshots/Hackathon02.png?raw=true "Sitecore Hackathon")

<br><br>
3)	Apply Trigger EXM Mail - Action Method to Your Submit Button<br><br>
4)	Edit Trigger EXM Mail Action with proper Field for First Name, Last Name and Email Address
![Alt text](/Screenshots/Hackathon03.png?raw=true "Sitecore Hackathon")
We have created a speak layout and you must properly map first name, last name and email address.
<br><br>
5) Rebuild Index <br><br>
6) Publish Forms
    - /sitecore/Forms/Hackathon - With Sub-Items
<br><br>
7) Add Proper Email Settings and Publish Item
	- /sitecore/content/Email/Messages/Hackathon - With Sub-Items
    <br><br>
8) Publish Campaign
    - /sitecore/system/Marketing Control Panel/Campaigns/Emails - with Sub-Items
    <br><br>

## Usage

- Navigate to the page where you have added the form and submit the data.
![Alt text](/Screenshots/Hackathon04.png?raw=true "Sitecore Hackathon")
<br>
As you submit the form you'll see an email at your Inbox. If you have provided any link to an email click on the link. EXM will track the user and show you the result in the Dashboard. By this Marketers can track the user journey and generate the lead for their website.

## Video

[![Sitecore Hackathon Video](http://i3.ytimg.com/vi/3BPf0Uvzbg0/maxresdefault.jpg)](https://www.youtube.com/watch?v=3BPf0Uvzbg0)
