
<h1> MILESTONE PROJECT ONE</h1>


1.	### *Purpose of the project:*
________________________________________
The purpose of this project is to provide a game review website that serves to inform the user of Andrew’s reviews, and invite them to collaborate/request future reviews. The idea for this website is based on a blog that I started regarding computer games, using Weebly. I didn’t have any web development skills when I created the blog, and once I learned HTML and CSS, updating and upgrading my blog into a real website was the first thing that occurred to me. It started life as “grababrew” then was changed to “One more Turn” which I felt more adequately represents the feeling you have when a game is really good, and you don’t want to stop playing.


2. ### 	*User Goals/stories:*
________________________________________
<ol>
	
  <li>As a Potential Employer for a Coding Role, I want to view Andrew’s website, to see how he performs as a Full stack developer. I want to be able to navigate the website and compare it to others, of similar scope.
</li>

  <li>As a Potential Game buyer, I want to understand Andrew’s perspective on games I may be interested in, in the form of reading his reviews.
</li>

  <li>As a Potential Collaborator, I want to be able to contact Andrew directly through the site and have easy access to his reviews and social media presence. I want to be able to submit a game review request. 
</li>

<li>As a general user, I want to be able to navigate through the page easily, and not get trapped at the bottom of any single page.</li>
</ol>	
	


3.	###  *Stakeholder Goals*
________________________________________
To lead the user to read Andrew’s reviews and contact/connect with Andrew on social media/through a contact form if user is a potential collaborator or client.

To lead the user to read Andrew’s reviews and contact/connect with Andrew on social media/through a contact form if user is a potential collaborator or client




4.	### *Typography and colour scheme:*
________________________________________
<ol>
<li>Font - Exo and Sans serif. This is because they worked well in the Code Institute models (i.e., easy to read)</li> 

<li>Icons - taken from Font Awesome, mainly in order to comply with existing conventions, e.g., a house or similar to represent the Homepage.
</li> 

<li>Colours – muted use of colours throughout, in order to draw visual attention to the review sections of the website. Red, white and black are the primary colours.
</li> 

<li>Images – photos and screenshots taken of games and game accessories (e.g. dice) to be used as icons for the relevant games, and background images for the relevant sections of the website. In CSS I used a filter to darken the images, so any text displayed stands out better. 
</li> 

</ol>


5. ### *Features:*
________________________________________

<ol>
<li>Header to consist of the website name, along with links to the Home Page, Video games review section, Tabletop games review section, About webpage and a contact page (essential!). In the future, this may be expanded to include Playthroughs, forum, gallery and podcast sections. (non-essential)
</li> 
	
<li>Footer to consist of social media links and the website name again (essential) and in the future this could be expanded to include a Patreon link, and an additional call to sign up (non-essential).
</li> 

<li>Homepage. The intent of the homepage is to provide a visually appealing but clean, minimalist introduction to the website, with a concise description of the website and 2 images that link to the review sections of the website.
</li> 

<li>Review sections- There are 2 review sections, one for digital (video, computer, console) games, and the others for tabletop (card, boardgames) games.

These will have a selection of game reviews, and the layout will be rows. When clicked upon, user is taken to a dedicated page for that review. At the top of the page there is a title and a brief introduction, and on each page there is a scroll to top button, to aid navigation.
</li>

<li>About. This is a simple page that outlines the philosophy of the website.
</li> 

<li>Contact. This page will be a simple contact/request for review form, with all fields obligatory.
</li> 

<li>Placeholder review - this is linked to reviews that are not yet complete, as it will take time to create proper reviews.
</li> 

<li> Thankyou page. This page exists to thank users who fill out the contact form.</li>

</ol>
The minimal viable product for this website is 

<ul>
	<li> header</li>
	<li> footer </li>
	<li> homepage </li>
	<li> review pages </li>
	<li> contact page </li>
	
</ul>


5.	### *Wireframes:*
________________________________________
The wireframes can be accessed from the "wireframes" folder, and also directly here:

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/wireframes/MS1%20mobile.bmpr

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/wireframes/MS1%20mobile.pdf

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/wireframes/MS1.bmpr

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/wireframes/MS1.pdf


6.	### *Technology:*
________________________________________
The website was created using Bootstrap, html5 and css3. No JavaScript was used, except what is bundled with Bootstrap. I originally built this website without any bootstrap, as I felt intimidated by the Bootstrap learning curve. However, I could not get the viewports to work consistently when testing it, so I rebuilt the website using Bootstrap. The main utility of Bootstrap in this website was in providing a header that collapses on smaller viewports, and also built-in scaling for various viewports.


When I started the website, GitHub and Gitpod were experiencing some issues, so I did the initial coding in visual studio code. I then migrated this to Gitpod and GitHub.

Resources:

GitHub - used to host the pages.

GitPod - usually accessed by using GitHub, used to edit the pages.

Visual Studio Code - backup editor. Please note that since the project began, GitHub has migrated away from the Theia framework onto Visual Studio Code.

Bootstrap CDN - used to structure the pages.

Font Awesome - used for icons.


7.	### *Testing:*
________________________________________

#### 7. 1 Code validation:

I used https://validator.w3.org to validate the html and https://jigsaw.w3.org/css-validator/ to validate the CSS. 

There were some minor errors (like lone div tags) in the HTMl but the CSS threw up very many errors, ALL of them related to Bootstrap, saying things like "ms flex box not recognised."


#### 7. 2 Test cases/ Testing the user goals/stories (section 2):



###### i. Potential employer goals:

a.	Upon entering the site, users are greeted with a visually attractive homepage, and a clearly visible and easy to navigate header and footer.

b.	The homepage immediately establishes the 2 purposes of the website.

c.	The user has two main (or obvious) options, which are to go to the tabletop or digital review sections) and others, enabled by the navigation bar.

Full screen Homepage 
![image](https://user-images.githubusercontent.com/77354731/114919020-ab4c2100-9e1f-11eb-82cc-7f529594b340.png) 


Example mobile screen Homepage 
![image](https://i.imgur.com/oEOaC9b.jpg)  




###### ii. Potential game buyer

a.	Upon entering the site, users are greeted with a visually attractive homepage, and a clearly visible and easy to navigate header and footer.

b.	The homepage immediately establishes the 2 purposes of the website.

c.	In the tabletop and digital review sections, each individual review is clearly indicated, with introductory text to serve as a synopsis and taster for the reader.

d.	Choosing a review opens up a separate page, with a back to top button to enable easy scrolling back to the top, and a back to tabletop/digital games button, so allow the user to easily return to main games review area.  The colour scheming for these accords with the header and footer, to maintain visual consistency.

Full screen Tabletop Review section:

![image](https://user-images.githubusercontent.com/77354731/114920011-e3079880-9e20-11eb-8ceb-1df6ac2d236a.png)

Example mobile Tabletop Review section:

![image](https://user-images.githubusercontent.com/77354731/114920081-f4e93b80-9e20-11eb-8247-1408875a5b2f.png)






###### iii. Potential collaborator

a.	The header has a prominent “contact” button, allowing users to submit review requests.

Full screen Contact page:

![image](https://user-images.githubusercontent.com/77354731/114920178-12b6a080-9e21-11eb-8715-57c95b205713.png)

Example mobile Contact page:

![image](https://user-images.githubusercontent.com/77354731/114920339-3ed22180-9e21-11eb-9793-8153d72374e1.png)





###### iv. General users:

a.	Upon entering the site, users are greeted with a visually attractive homepage, and a clearly visible and easy to navigate header and footer.

b.	The homepage immediately establishes the 2 purposes of the website.

c.	On the tabletop and digital reviews sections, there is a short introduction at the top of the page, so users can easily identify where they are, and the purpose of that page.

d.	There is also a scroll to top button that is always easily visible and accessible, which allows users to always get back to the top of the page, no mater how far down they have scrolled. This is also useful for the future, as more reviews get added. The colour scheming for these accords with the header and footer, to maintain visual consistency.

e.	In individual reviews, there is a back to top and a back to tabletop/digital reviews button.

f.	In the placeholder review page (where users are directed if there is no review yet) there are 2 buttons, to easily direct the user to either the tabletop or the digital review section.

Full Screen Placeholder Review page:

![image](https://user-images.githubusercontent.com/77354731/114920487-65905800-9e21-11eb-8385-8300c6c2dc05.png)


Example Mobile Placeholder review screen:

![image](https://user-images.githubusercontent.com/77354731/114920999-f9622400-9e21-11eb-9de5-f6b3d2c4872d.png)




#### 7. 3 fixed bugs:

I did not encounter many bugs the second time around, although I did have some issues positioning the text form for the contact webpage. I solved that by initially setting all margins to auto, and using "justify content center," "align items center (when needed,)" and then adjusting the margins and padding to get the desired appearance.

I also had some issues with gaps appearing between images, with white space showing, which was not wanted. I solved this by using "no gutters" when constructing the rows and columns.


The images in the review pages were not displaying correctly on Tablets, namely the Kindle HDX and iPad, but not the iPad Pro. Experimenting revealed that "col-md-6" was causing images to take up only half the row, so removing it fixed this issue.

Feedback from the initial submission indicated some issues with errant html commenting in the deployed code, alongside issues with viewports, especially on the iPad and Kindle formats. These have been resolved. There was an image in the crusader Kings 2 review that was causing problems on smaller viewports, setting the CSS here to max-width: 100% solved the problem.

The footer was not rendering well on smaller viewports, which was solved by adjusting the padding settings.

#### 7.4 supported screens and browsers


There are screenshots, available in the screenshots folder, that show the website working at fullscreen, and also at example mbile (Iphone 5) viewports.

The screenshots are also available here:

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/full%20screen%201.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/full%20screen%202.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/full%20screen%203.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/full%20screen%204.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/full%20screen%205.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/full%20screen%206.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/mobile%201.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/mobile%202.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/mobile%20%203.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/mobile%204.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/mobile%205.jpeg

https://github.com/ANDREWAHN-UK/MS-one-more-turn/blob/a2eae712ee38fd4ea43281f81ae719c09f0d7b28/screenshots/mobile%206.jpeg






I used Opera, Edge, Firefox and Chrome, and tested these, along with general usability, using the dev tools there.

Dev tools in Chrome by right click + inspect + toggle device toolbar + select various devices.

In Opera right click + inspect + toggle device toolbar + select various devices. 

In Firefox, right click + responsive design mode (ctrl+shift+m) + select various devices. NB that Firefox displays this all at the bottom, not the right side like the others. 

In Edge right click + inspect + toggle device emulation + select various devices.


The procedure for testing was as follows:

<ol>
	<li>In style.css set up media queries for the viewports, in descending order (i.e. starting with the Ipad Pro and ending with the Galaxy Fold)</li>
	<li>introduce a new element, or change, e.g. a "scroll to top button."</li>
	<li>style it for the desktop, using dev tools and style.css.</li>
	<li> when happy with this, use dev tools for the next viewport, in descending order (i.e. starting with the Ipad Pro )</li>
	<li>Repeat for each element and page, e.g. styling the padding and size of the social media icons.</li>
	<li>Save changes via github commit and push</li>
	<li>Open up website on mobile device. I have an Oppo X2 Lite</li>
</ol>



There were several buttons introduced to aid navigation:

<ul>
	<li>Scroll to top (Crusader Kings 2, Tabletop, Digital sections)
</li>
	<li>Return to digital reviews section (in placeholder, Crusader Kings 2 sections)</li>
	<li>Return to tabletop reviews section (in placeholder section)</li>
</ul>
	

These have been tested and adjusted at various viewports, so there is consistent styling, specifically that the text is removed, and a heavier reliance placed on icons at smaller viewports. The colour scheming for these accords with the header and footer, to maintain visual consistency.


Further testing was done with friends and family, and by submitting the code for peer review on slack, using fresh eyes to test the UX, most notably ease of navigation between pages, and visibility of text against coloured backgrounds.

Results of this testing led to the introduction of the aforementioned buttons and an introduction at the start of the Tabletop and Digital reviews sections, and a filter on the inital images (i.e. the index.html) so the text would be more contrasted.

There were some readability issues with the Crusader Kings 2 review, rectified by adjusting the margin-top and the padding properties, also tested on all viewports.



8. ###  *Deployment:*
________________________________________
GITHUB: https://andrewahn-uk.github.io/MS-one-more-turn/

NETLIFY: https://naughty-khorana-5e9348.netlify.app

 #### 8.1 Github:
I used GitHub pages and Netlify to deploy the website.

When I began, there were some issues with GitHub, including a server temporarily overloading at one point, but recently there have been no problems.

To deploy the website: 

<ol>
	<li>go to github.com and log in </li>
	<li>locate the list of repositories, top left of screen</li>
	<li>click on the required repository, in this case https://github.com/ANDREWAHN-UK/MS-one-more-turn </li>
	<li>on the top, locate the setting button, click on this 5- scroll down until you see the heading "GitHub pages," click on the link </li>
	<li>the URL in your browser should read: https://github.com/ANDREWAHN-UK/MS-one-more-turn/settings/pages </li>
	<li>under "source" there should be a message like this: “Source GitHub Pages is currently disabled. Select a source below to enable GitHub Pages for this repository.” 
</li>
	<li> select the appropriate source (choose branch: master) and click save. 
</li>
	<li>there will now be a message that reads:" Your site is ready to be published at" followed by a link, in this case: https://andrewahn-uk.github.io/MS-one-more-turn/ 
</li>
	<li>click on it to make sure it works.</li>
</ol>



NB, at step 7, if your page has been published before, the message will read: "Your site is published at https://andrewahn-uk.github.io/MS-one-more-turn/"

GitHub is the preferred website for the Coding institute.

To create a fork/backup:

GitHub does not currently allow you to directly fork your own repo, but there is a workaround:

<ol>
	<li>make a note of the URL of your repo, e.g., "https://github.com/ANDREWAHN-UK/MS-one-more-turn" </li>
	<li>at the very top right of the page, next to your login image and the bell icon, there is a + button, click this. </li>
	<li>click "import repository”. </li>
	<li> Where it says, "Your old repository’s clone URL," put in the URL of your repository, e.g., "https://github.com/ANDREWAHN-UK/MS-one-more-turn"</li>
	<li> In the "repository name field" choose an appropriate name for your new repository </li>
	<li>Click "begin import" </li>
	<li>You now have a copy of your original repository, with all commit history and branches!</li>

</ol>


However, be aware that this is not a real fork, and so you cannot do pull requests back and forth.

Because this effectively clones the repo, I decided against using the actual clone feature, but information on that can be found here:

https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository

#### 8.1: Netlify:

I chose Netlify because it connects very easily to GitHub and is thus a very suitable backup.

For Netlify: 
<ol>
	<li>got to https://app.netlify.com/</li>
	<li>log in using one of the available options (I used GitHub) </li>
	<li>Once logged in, click the button that says, "new site from git."</li>
	<li>Choose the appropriate git source, in this case GitHub.</li>
	<li> A selection of the relevant repositories will show up, click the desired one, in this case "ANDREWAHN-UK/MS-one-more-turn”. </li>
	<li> On the next page, when you are happy with the options, click "deploy site”. </li>
	<li> Once the website has been deployed, on the next page, near the top, your website name and URL will be available, in this case:

naughty-khorana-5e9348 https://naughty-khorana-5e9348.netlify.app/</li>
	<li> Click on it to make sure it works.</li>

</ol>



9. ###  *Credits:*
________________________________________
Code:

Done by myself, with some work done by Bootstrap, most notably the navigation bar.

Content:

All done by me, with ideas and inspiration for writing and layout from the following websites:

<ul>
	<li> https://mongolcult.com/ </li>
	<li> https://www.quartertothree.com/fp/ </li>
	<li> The Scientific Gamer | Science, gaming, and all things in between. https://scientificgamer.com/ </li>
	<li> PC Gamer https://www.pcgamer.com/uk/ </li>
	<li> https://explorminate.co/  (this last actually published my Troy: Total War review, which will get added to this website soon).</li>
	

</ul>

	

Media:

<ul>
	<li> https://unsplash.com/ for most of the images used.</li>
	<li> Steam https://store.steampowered.com/ for computer games images.</li>
	<li> Google.com for some computer games images.</li>
	<li> Boardgame Geek https://www.boardgamegeek.com/ for tabletop images.</li>
	<li> Font awesome https://fontawesome.com/ for the icons. </li>
	<li> Johan Lundquist at Artstation, for the CK2 review background image https://www.artstation.com/artwork/nvdX6</li>
	

</ul>
	

Acknowledgements:

<ul>
<li>Code Institute slack community, tutor support and mentor (Rohit Sharma)</li>
<li>Troy Costick (devildog) at Explorminate.co, for allowing me to write for his site.</li>
</ul>


