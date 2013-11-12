#AutoPilot Community Edition

##Introduction

Community Edition will consist of a special version of the software that allows users to use full AutoPilot capabilities on a limited range of machines. The Community Edition will be released paired with a website for the users of CE that supplies resources and is designed to build a community around AutoPilot users. The website contains tutorials and screencasts that introduce users to AutoPilot functionality and teach them how to operate AutoPilot.  

On this page we collect information, questions and other related information pertaining to AutoPilot Community Edition planning.

##Discussions

11.11.2013 (FCO, VV, RJ, MN)#

We will ship AutoPilot CE on three (four) VMs. A new user interface (configuration wizard) will be created that leads users through cluster configuration. The configuration wizard will be designed to aid Community Edition users but once it's functional will also be shipped with the full release to simplify configuration.

##Unanswered Questions

Q Where should information be available?  
Q Should we fork repo.tabtab.org?  
Q Should we refactor repo.tabtab.org and split CE site into two different projects?  
Q Should we create a new site for community users?  
Q What format will the information be published in (web, pdf)?  
Q Where will we host screencasts?  
Q How can we make sure users don’t use more than five machines?  
Q What are the steps if they do use more?  
Q How can new users register for AutoPilot CE?   
Q How will the licenses for these users be generated? (Manually can only work for a short period of time)  
Q Should we use the black theme for a potential new site? (like the Self-learning and CE landing page)  
A: Marco Zinn, 29.10.2013: We should not use a black theme since that will impact usability and be hard to work with for many users.  
Q What is the proposed release date for AutoPilot CE?  
Q How can we free resources within technologies to complete CE in time?  
Q In what format will we release CE (rpm? Repository or single package download?)  
Q How can we deliver support?  
Q What do we answer people who want to use CE on other platforms than RedHat/SLES/CentOS?  
Q Which parts of documentation should be available for CE?  
Q How do we handle updates/upgrades for CE?  
Q Which release will be included in CE (4.1, 4.2?)  
Q How do we verify the number of licenses obtained by a single user? (Can I get several licenses with different email addresses)  
Q What would a disclaimer for CE look like?  
Q How do we manage/facilitate user interaction?  
Q Should we allow anonymous access to communication?  
Q Will user credentials for the communication channel require license information?  
Q What will the pricing for “full AutoPilot” upgrade look like?  
Q Should we provide a “older” version for Community Edition to entice people to upgrade to pay version?  
Q Can we implement restrictions that don’t impact the power of AutoPilot but entice people to upgrade?  
Q How do we teach people to build MARS models? (if only five machine nodes we could provide a basic mars schema to fill in)  
Q Will we provide example KIs?  
Q How do we teach people to construct new KIs?  
Q Do we use new resources to power the community site?  
Q Can wen use existing structures to power the community site?  
Q How do we provide access to schema files?  
Q Should there be a limited number of initial CE users?  
Q How will users report bugs?  
Q How will users be able to give general feedback?  
Q What would an open landing page for CE look like?  
Q How will we manage user access for the “registered” users? (Database, where do credentials come from, how to restore passwords)?  
Q What data will we store for and by users?  
Q Will/Should there be an “application process” for CE? (state what you want to do with AutoPilot to get access)  
Q Who will manage the community?  
Q Who will answer questions posed in the community that find no answer from other users?  
Q What graphical distinction between CE and regular AutoPilot will there be?  


#Proposals

##Merge Community Edition and "Demo"

In the long run we should merge demo version and community edition. What justifies basically maintaining three release versions of AutoPilot? The demo version could be a “default” mode of Community Edition where it doesn’t use persistent storage in absence of a license file. Once the user has obtained/supplied a license file he can have persistent storage for a limited amount of machines. The user should be able to upgrade to a “full license” that keeps his current configuration and data but allows AutoPilot to use the full feature set.
Q Who is actually using the demo version to develop against?
Identify software features via license#

The distinction between full, demo and community editions of AutoPilot will be governed by the license file employed. This reduces development overhead since we only maintain a single codebase that can be tested in one swoop.
Q Which arguments stand against using a license file to control AutoPilot features?

##MOCKUP CE Website

Landing Page Logo Symbolic Picture arago Logo Imprint Login/Register (registration via captcha) Contact

MAIN PAGE Welcome Text (Links to Introductions to Elements)

##NAVIGATION

Home How it Works  
AutoPilot principles  
Knowledge based Automation  
Knowledge Items  
MARS IT Model  
Documentation  
Installation  
Repository  
Packages  
Tutorial  
Knowledge Items  
Knowledge Item Introduction  
Knowledge Item Tutorial  
Knowledge Items Syntax  
MARS  
MARS Model Introduction  
MARS Model Tutorial  
Example MARS Model
Mars-o-matic.com Link  
Support  
Discussion  
Feedback  
Screencasts  
Introduction to AutoPilot CE  
Installing AutoPilot CE  
Creating a MARS Model  
Designing a Knowledge Item  
Upgrade  
Pricing  
Training  
Offers  
Develop for AutoPilot (repo.tabtab.org)  