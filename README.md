![Hackathon Logo](documentation/images/hackathon.png?raw=true "Hackathon Logo")

# EXM Email Submit Action in Sitecore Forms

This Module is created during Sitecore Hackathon 2019.

## Authors:
- Senthilvel Subramanian
- Nikki Punjabi
- Ashish Bansal

## Sitecore Hackathon Category
- Best enhancement to the Sitecore Admin (XP) UI for Content Editors & Marketers

## Sitecore 9.1 Module (Module install package)
   - https://github.com/Sitecore-Hackathon/2019-Burj-Knight-Riders/blob/master/SitecorePackage/Create%20Profile%20and%20Trigger%20EXM%20Mail%20using%20Sitecore-0.1.zip

## About Create Profile and Trigger EXM Mail using Sitecore Forms

This module is really very important for the marketers who want to generate the leads for the website using Sitecore Forms. In this module, we have extended Sitecore Forms default functionality by creating a contact in the Sitecore and trigger EXM Mail.
We have extended the submit action functionality to perform following:
    -	Create Contact – We are creating Sitecore contact using Sitecore Form fields [First Name, Last Name and Email Address] – For the same contact, we can track the activity in Experience Profile.
    -	Trigger EXM Campaign – This is most wanted feature required for the marketers who want to send the pre-defined email template on form submit action, for example, Thank You Template, Order Confirmation template, subscription thank you., etc.

So, in this we are providing the functionality for the marketers to choose automated EXM Campaign during the submit action.

##Problem: 
Marketer want to create a form and want to have an email sending functionality and track the lead of the website for their future interaction.
    -	But there is no option for Marketers to send EXM Mail without creating the contact in Sitecore, using Sitecore Forms.

##Solution:
We focused on both the above key problems where marketers can send email of there own choice based on the form behavior and in the background the form lead will be converted into the Sitecore contact, which marketer can further analyze in the experience profile.

##How to use this module:

Install the Module in your Sitecore Instance and Follow the post installation steps properly as listed below:

1)	Set Email SMTP for EXM if it is not configured.
    o	Or more details refer | Custom Email SMTP configuration: http://sitecoresolution.blogspot.com/2018/10/setup-your-first-email-with-sitecore-9-EXM.html



- Precise and Clear Installation Instructions document (1 – 2 pages)
- Module usage documentation on [Readme.md](documentation) file on the Git Repository (2 – 5 pages)
  - Module Purpose
  - Module Sitecore Hackathon Category
  - How does the end user use the Module?
  - Screenshots, etc.

- Create a 2 – 10 minutes video explaining the module’s functionality (A link to youtube video)

  - What problem was solved
  - How did you solve it
  - What is the end result
