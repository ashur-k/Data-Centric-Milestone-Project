[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/ashur-k/Data-Centric-Milestone-Project) 

# Bend River Media
### I have developed the website for Bend River Media (BRM), the company name for the award-winning photographer Benjamin (Ben) Driver. BRM offers a wide range of photography and videography services in the following areas.
###### •	Wedding Photography and Videography
###### •	Headshots Photography
###### •	Landscape Photography
###### •	Product Photography
###### •	Commercial Videography
###### •	Performances Showreel Videography
The website for BRM has been designed to look simple, elegant and easy to navigate. The home page, which gives brief information about photography and videography services provided by Bend River Media, has two ways of navigation. Customers can either use the fixed navigation bar at the top of the page or use the navigation buttons provided in each brief information section. Both of these lead potential customers to the services in which they may be interested. 
# UX
Ben Diver is a creative photographer and videographer and winner of the Royal Television Society (North-East and Border 2018) award for his drama video, “Develop”. He asked me to build him a website which would enable him to market his skills to a range of potential customers. For example:
###### •	As a mother I want a series of portraits of my two children.
###### •	As we approach our wedding, we want a professional record of our day.
###### •	As an auditioning actor I need professional headshots for my resume.
###### •	As a performer I need a video record of an upcoming performance.
###### •	As a micro brewer I need marketing material for my artisan beers.
###### •	As a local church we need a videographer to market our events.
###### •	As an interior decorator working in the commercial sector, I need inspiring and calming landscape images.
The aim of the website is to market Ben’s services and to help him to generate business. Ben and I looked at different websites which provide similar services to Ben’s business. I needed to get ideas of how he wanted his website to look and soon realised he wanted something visually simple and easy to navigate. Ben wanted separate web pages for each of the different services he provides. For this reason, designing the navigation of the website was a challenge. I wanted web users to find the services they were looking for easily and after taking feedback on several different versions I decided on the current one, which is simple, stylish and easy to read. I used Balsamiq Mockups 3 and made a wireframe design and Ben and I agreed on this final design.
# Features
###### 1.	The website markets the full range of Ben’s services. It is designed to be time efficient for web users. 
###### 2.	Each section provides links to the main page of that particular service.
###### 3.	To make the website consistent each service page has an introductory hero section with a fixed background image.
###### 4.	Each of these pages has a link to a contact form.
###### 5.	The BRM website has a fixed navigation bar at the top of each page, which gives users full control over navigation.
###### 6.	The BRM website design is device responsive, it’s designed for mobile, tablet and large screen devices.
###### 7.	BRM has a web form which helps users to send information.
###### 8.	BRM customers are also provided with social media links where they can find more information.
# Features Left to Implement
At the moment there is no custom script applied to any section of the website. In particular the form modal is not functioning correctly and needs scripting in order to be complete. In the future I will implement data validation and form submission. 
# Technologies Used
###### •	HTMI5 to implement website project.
###### •	CSS3 to implement website project.
###### •	GIT POD online web workspace for HTML & CSS coding.
###### •	Git Hub hosting services and data storage services.
###### •	Google Chrome to run GIT POD workspace for development process. 
###### •	Google chrome Git extension button to log into Git Pod workspace.
###### •	Google Chrome Developer tools.
###### •	Firefox browser latest version for testing purposes.
###### •	Opera latest version for testing purposes.
###### •	Safari unknown version for testing.
###### •	EDGE latest version for testing purposes.
###### •	Internet explorer latest version for testing purposes.
###### •	Bootstrap 4 to implement website.
###### •	Font awesome free version.
###### •	Balsamiq Mockups 3 for designing wireframes

# Testing
The Website was tested in different browsers at each stage of its development, for example Opera, Mozilla Firefox, Apple Safari. Opera, in particular, gives more control over media playback. Ben didn’t want audio for his home page video, so I showed him a version of the video section with a small button to mute/unmute the video. He didn’t want web users to have that control. However, when I informed him Opera Browser will give that control to users, and asked what he thought about that, he told me he is fine with what Opera browser is offering.
The website has been tested on different mobile devices, tablet devices, and desktop screens. At the moment I am confident that the website keeps its integrity on all sizes of screens. I have tested it on Google Chrome’s developer tools, particularly I have used responsive developer mode to check if the website loses its integrity on any screen size.
I used a desktop-first approach as Ben wanted me to make website primarily for desktop users. In the starting phase I encountered problems with the website losing its layout on mobile and tablet size screens. I was not familiar with Bootstrap grid system and I explained to my Code Institute tutor, Anna, that my knowledge was not sufficient to implement Bootstrap grid system in my project. She encouraged me and informed me that this was a common problem many students had faced. Anna directed me to her Youtube video, which is made for Code Institute students and explained the Bootstrap grid system in more detail. After watching that video, I was able to use the Bootstrap grid system and my website layout was correct on different screen sizes.   
During my testing I faced a technical problem where there was a thin white line under all my Bootstrap carousel images. In my discussions with Tim, another code institute tutor, it was pointed out that my website was losing its layout integrity on his screen size. Tim gave me his screen width and height, for which I added media queries. The thin line was coming because Bootstrap class naming and my custom class naming were conflicting. Bootstrap Carousel had the active class applied so it got styling information from the Bootstrap active class and my custom class. I renamed my CSS class to (. activee) which was applied to the active navbar menu item. Once I changed the name of that active class the thin line disappeared. During that conversation I resolved two problems, one of which I was aware and the other I wasn’t. 
I coded the website with the help of CSS variables and all variables were added to the top section of CSS code. Doing this allows me quickly to test what looks good on the website. For example, if I want to choose the standard colour, I just need to change one variable, not go to all sections of code to change that one colour. This feature has made testing very easy. During development I showed different colours, font families and sizes to Ben and other people who I used as test-users to evaluate if it’s an efficient website and what works best.
At the moment there is a Modal feature of the website Contact-us form which is not functioning correctly. It drops down from the top-centre of the screen and reports that the information has been sent even when fields are not filled in. I have been told that I need to write JavaScript to solve this problem, which I will be able to code once I have advanced to the next module. 
On each commit to GitHub website, links were distributed to different users to get their feedback and to check the new version.
Each contact-us form field has a required attribute which is there to make sure user adds valid information. 
Deployment
The website is deployed using GitHub web hosting service. (https://ashur-k.github.io/Data-Centric-Milestone-Project/wedding-services.html). 
The website is also downloaded on my personal computer from a “clone and download” link provided by GitHub.  I have downloaded various versions of the website, at various points, and deployed them on my local machine for testing.
# Credits
# Content
All textual content was provided by Ben Driver. 
# Media
All pictures and videos used are spectacular examples of Ben’s work.
# Acknowledgements
I want to thank Dave Blackman, Henry Cheng and Ismail Topuzi who have given me feedback on the website during the development phase.
I have read code from https://www.w3schools.com/ , Stack overflow and Bootstrap documentation. I have taken snippets of code from the above website and then re-written them into my code. 
I have watched a number of Youtube videos, particularly from Traversy media and other Youtube channels. , I have implemented some features from these videos in my code.
Particularly the w3school website taught codes allowed me to have more than one background image in a container. Without having that ability, I was not able to keep design standards consistent throughout the website.


