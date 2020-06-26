# Milestone 1 Project - YOGA FLOW

My first milestone project has been put together based on my learnings from the 1st to the 5th modules of the Full Stack Developer course with Code Institute. This includes HTML, CCS, and user-centric front end development.

YOGA FLOW is a fully responsive, custom-built website which has been designed and built with the users needs first.

You can view the live site here: [YOGA FLOW](https://michellelclement.github.io/yoga-flow-ms1/)

![YOGA FLOW mockups on various devices](/readme-docs/mockups.jpg)


## UX
YOGA FLOW is a new Yoga studio. It is currently finding its feet and looking to grow its customer base.

External Users Goals: The YOGA FLOW website is for current and new customers to learn about the Yoga Studio and view the timetable of classes available to them. It also informs them of how to attend a class, and where to locate the studio.
Using simple and clear navigation, a clear schedule and informative text, YOGA FLOW will be able to provide the answers to the user questions.

* As a user, I want to be able to see what classes are happening and on which days and times
* As a user, I want to be able to locate the studio
* As a user, I want to know how to attend a class
* As a user, I want to be able to contact the Yoga studio

Site Owner’s Goal: The studio is looking to attract new customers and to minimise class enquiries by providing a clear class schedule and information on how to attend a class.
* As the site owner, I want to be able to inform visitors of the class schedule
* As the site owner, I want to be able to inform visitors of the location of the studio
* As the site owner, I want to be able to inform visitors how to attend a class

## Wireframes
I took the above user stories and put together the website layout into wireframes. I used [Balsamiq](https://balsamiq.com/) to create these for desktop, tablet and mobile screens for each page of the website, showing how elements would differ depending on the varying screen size.
I did not deviate from the original wireframes, other than adding the map image to the mobile view as I believe it improved the user experience, and also with specific styling of elements such as making the footer icons smaller. 

Below are the wireframes for the homepage. [You can view all of the wireframes, including the additional pages here](wireframes/wireframes-yoga-flow.pdf)

![Homepage wireframes](/readme-docs/wireframes.png)


## Features
Navigation: The main navigation includes a link to each of the main sections of the site, which answer each of the user questions, and is styled clear, simple and modern.

Class Schedule: I created a simple, clear and easy to read table using [Bootstrap](https://getbootstrap.com/) which allows the user to find a class. It provides all the information needed for those wanting to know what classes are on, and on which days. The table is also clear and easy to read on mobile devices. There are many CTA's to this section on the homepage plus a link in the main navigation named 'Find A Class.'

Contact form: A simple form on the Contact page, again using [Bootstrap](https://getbootstrap.com/) allows users to send their queries directly to the site owner. A link to this page can be found easily in the main navigation.

Future features: Whilst the site currently states that the classes are on a 'drop-in' basis, a future feature that would benefit the site owner would be a class booking feature. This would be beneficial when the studio becomes very popular and needs to limit class sizes.


## Technologies Used
I used a number of languages, frameworks and tools to construct my website. These include;

* [HTML](https://html.com/)
* [CSS](https://www.w3.org/Style/CSS/Overview.en.html) 
* [Bootstrap](https://getbootstrap.com/)
* [GitHub](https://github.com/)
* [GitPod](https://www.gitpod.io/)


## Tools Used
* [Balsamiq](https://balsamiq.com/) - Used to create my wireframes, showing the positioning of elements on varying screen sizes.
* [Adobe Photoshop](https://www.adobe.com/uk/products/photoshop.html) - Photoshop was used to create my map image
* [Adobe Color](https://color.adobe.com/create) - This tool helped me to select my complementing colours
* [W3C HTML Validator](https://validator.w3.org/) - I used this tool to check the validity of my HTML code.
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - I used this tool to check the validity of my CSS code.
* [Autoprefixed](https://autoprefixer.github.io/) - I used this tool to check the prefixes of my CSS code.


## Project Setup
Upon starting my project, I used a blank repository rather than using the Code Institute template. Once I was informed of my mistake by my mentor, I restarted my project using the correct template.

As I had completed a lot of the index.html document in the original repository, I simply copied and pasted this code to the new template. For this reason, the start and bulk of my index.html file has very few commits.
Initial and frequent commits for the index.html page are stored in the original repository, [which can be viewed here.](https://github.com/michellelclement/yoga-flow)


## Testing

**W3C HTML Validator** – code run through the validator to check there were no syntax errors
* Ran index.html though validator: 
    * Passed with no errors
* Ran findaclass.html though validator: 
    * Passed with no errors
* Ran contact.html though validator: 
    * Passed with no errors


**W3C CSS Validator**
* Ran style.css though validator to check there were no syntax errors: 
    * Parse error found
    * Corrected parse error with missing } at end of code
* Ran style.css through validator again
    * Passed with no errors


**User stories**

* * As a user, I want to be able to see what classes are happening and on which days and times
    * A clean, clear and simple navigation bar is visible as soon as a user lands on the site. The menu item FIND A CLASS clearly states that the user will find information of the studios classes once clicked. 
    * Multiple CTA’s with the same title can be found throughout the homepage.
    * Both of these options give the user multiple ways to reach the page where they can find out about the classes.

* * As a user, I want to be able to locate the studio
    * The clear and simple navigation bar is visible as soon as a user lands on the site with the menu item LOCATION, clearly stating that the user will find information of the studios location once clicked. 
    * This navigation link takes the user to an anchor point on the homepage which includes the studio address and an illustrated map. 
    * The location information is held on the homepage, so a user can also find these details if they scroll through the homepage.
    * Both of these options allow the user to find the location details they require quickly.
 
* * As a user, I want to know how to attend a class
    * Information on attending a class is included on the FIND A CLASS page, which can be accessed easily via multiple CTA’s and main navigation links as mentioned above. 

* * As a user, I want to be able to contact the Yoga studio
    * A CONTACT menu item can be found in the main navigation which is visible and available to the user as soon as they land on the site. 
    * The user can contact the Yoga studio by clicking the clear CONTACT button in the main navigation and filling in the form on the CONTACT page.
    * The Contact form means the user can send their message directly through the site and do not need to leave the website to send an email from another page or service.


**Further testing**
The website as tested on Google Chrome, Internet Explorer and Firefox browsers.
The website was viewed on a variety of devices including Desktop, Laptop, iPad, and the mobile options provided by Google chrome developer tools.

A full breakdown of tests can be found [in the document here](/readme-docs/testing.pdf)


## Design

**Colours:** 
I decided to stick to a very simple colour pallet which complements the Yoga mindset and audience. I wanted to use a soft coral/orange colour, complemented by a green shade. I used [Adobe Color](https://color.adobe.com/create) to pick the perfect color combinations. 

Here are the colours I chose via Adobe Colors, from which I selected two.
![YOGA FLOW color options](/readme-docs/adobe-color.png)

* Nav & Footer background: #FAFAFA 
* Text: #212529
* Body background: #FFF
* CTA Buttons: #FF8970
* Green: #70FFC7 (unused)

Upon styling of the website, I decided that, due to the lovely colours of the photography, one accent color was enough and two was unnecessary. I decided to stick with the soft orange/coral shade of #FF8970 to highlight CTA's. This colour also complimented the imagery, as well as the off white and a dark grey.

**Typography:** 
For the typography, I wanted to use a simple font that fitted with the calming nature of Yoga. I chose Quicksand for this reason due to both regular and capitalised text fitting this  requirement, as well as the font being clear and legible on smaller devices. The font was installed into the head element of the HTML files, with a backup front of 'Sans-serif.'

**Logo:**
the YOGA FLOW logo was created by myself, simply using the Quicksand font in uppercase, and a thicker font weight (600) to the rest of the website to make it stand out as the brand.


## Deployment
I deployed my YOGA FLOW project website using GitHub pages by the following steps:
1. Loging in to my GitHub account and locating my repository
1. Clicking on the settings icon (near the top right of the page)
1. Scrolling down the page to locate the 'GitHub Pages' section
1. I selected 'Master branch' in the dropdown
1. This deployed my project to the URL: https://michellelclement.github.io/yoga-flow-ms1/

[Click here to view the live YOGA FLOW website](https://michellelclement.github.io/yoga-flow-ms1/) 



## Credits

**Content**

Website text: All website text was written by myself for this project specifically.

Website colors were finalised using Adobe Color.

**Media**

Photography Images: All photographs used were downloaded from the Royalty Free image website [Pexels](https://www.pexels.com/)

Location map: The map image was created by myself using [Adobe Photoshop](https://www.adobe.com/uk/products/photoshop.html)

### Acknowledgements

Thank you to fellow student and Slack Channel member Anthony O' Brien for helping me with some media query questions, and helping test my project on his Huawei device.

Thank you so Malia Havlicek for reviewing my website in the Peer-Code-Review Slack Channel

Thank you to fellow student Jos Velema. Whilst looking for assistance on linking the Hamburger Menu on the slack channel, I found his discussion with Marc Veldhuis who was looking for the same assistance. Jos pointed out Marc's mistake of not adding in the Bootstrap JavaScrip CSS tag, which fixed my problem also.

And finally a big thank you to my mentor Antonija Šimić!

In addition to assistance from my mentor and the Slack community, I also received some assistance in writing or troubleshooting my code from previously answered questions on the following websites:
* [Stack Overflow](https://stackoverflow.com/)
* [w3schools.com](https://www.w3schools.com/)