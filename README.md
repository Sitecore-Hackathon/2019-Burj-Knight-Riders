![Hackathon Logo](documentation/images/hackathon.png?raw=true "Hackathon Logo")

# EXM Email Submit Action in Sitecore Forms

This Module is created during Sitecore Hackathon 2019.

## Sitecore Hackathon Category
- Best enhancement to the Sitecore Admin (XP) UI for Content Editors & Marketers

## Sitecore 9.1 Module (Module install package)
   - https://github.com/Sitecore-Hackathon/2019-Burj-Knight-Riders/blob/master/SitecorePackage/Create%20Profile%20and%20Trigger%20EXM%20Mail%20using%20Sitecore-0.1.zip

## About Create Profile and Trigger EXM Mail using Sitecore Forms

This module is really very important for the marketers who want to generate the leads for the website using Sitecore Forms. In this module, we have extended Sitecore Forms default functionality by creating a contact in the Sitecore and trigger EXM Mail.
We have extended the submit action functionality to perform following:<br><br>
    -	Create Contact – We are creating Sitecore contact using Sitecore Form fields [First Name, Last Name and Email Address] – For the same contact, we can track the activity in Experience Profile.<br><br>
    -	Trigger EXM Campaign – This is most wanted feature required for the marketers who want to send the pre-defined email template on form submit action, for example, Thank You Template, Order Confirmation template, subscription thank you., etc.
<br><br>
So, in this we are providing the functionality for the marketers to choose automated EXM Campaign during the submit action.
<br><br>
## Problem: 
Marketer want to create a form and want to have an email sending functionality and track the lead of the website for their future interaction.
    -	But there is no option for Marketers to send EXM Mail without creating the contact in Sitecore, using Sitecore Forms.
<br><br>
## Solution:
We focused on both the above key problems where marketers can send email of there own choice based on the form behavior and in the background the form lead will be converted into the Sitecore contact, which marketer can further analyze in the experience profile.
<br><br>
## How to use this module:

Install the Module in your Sitecore Instance and Follow the post installation steps properly as listed below:

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
![Alt text](/Screenshots/Hackathon04.png?raw=true "Sitecore Hackathon")

And now you can test the form.  On submission, you should receive an email. If you have any link which comes back to your site, then it will track the user’s journey.

## YouTube Video:
[![Sitecore Hackathon Video](http://i3.ytimg.com/vi/3BPf0Uvzbg0/maxresdefault.jpg)](https://www.youtube.com/watch?v=3BPf0Uvzbg0)

## Authors:
- Senthilvel Subramanian
- Nikki Punjabi
- Ashish Bansal
