A complete website for the fine art ceramicist Daniel Harman. To increase awareness of the artists current work and his up-and-coming exhibitions. 

### Daniel Harman Artist Portfolio

#### User Experiences
User One - I would want the profile picture on the first page and then pictures of his work following, to get a faster vibe of the artist and work this way. I liked seeing the projects grouped on the first page. Easy style and aesthetics of the website. 
User Two- I enjoyed the colours of the site, the website flows nicely. 

#### Strategy 
* The core aim of the website is to showcase the artists portfolio, furthermore to raise the artists profile and to develop a customer base through the self promotion of the website.

* To provide supporting information for previous and upcoming exhitbitions. 

* Provide professional presentation of the artists work with the individual projects clearly seperated

* To provide a contact space for acquisition of artists’ work, to aquire general individual further information. 
 
* To provide a link to social media for a more relaxed view of the artists work and to provide an opportunity to see the artists work in progress.

#### Scope – Function
The site must be clear, and the images and work well define, to differentiate between the projects.
The site must be minimalist to not distract from the images of artists work. 

#### Scope – Content 
The ideal customer visiting the website would consist of individual and corporate galleries, private buyers as well as small boutique businesses. Private buyers would be from affluent social economical backgrounds. 
Visitors to the site would also include private curators for their clients as well as arts and ceramic students wanting to explore the work. 
Clearly illustrate who the artist is, inform the site visitor of the artists current exhibitions and the future exhibitions. 



#### Structure 

* A navigation bar
* A clearly defined homepage depicting anchored images of the artists different projects. 
* A selection of the artists projects on individual pages. 
* An About Page for the artist to be introduced. 
* A Contact Page for perspective buyers, exhibitors, curators, and individuals with a general interest in the artist work.  

#### Skeleton 

<img src="./Readme-media/full-frame.jpg" width= "200px" height="auto">
<br>
<img src="./Readme-media/contact-and-about-frame.jpg" width= "200px" height="auto">
<br>
<img src="./Readme-media/landing-frame.jpg" width= "200px" height="auto">
<br>
<img src="./Readme-media/project-frame.jpg" width= "200px" height="auto">

 

#### Surface 
Aesthetically for the site I decided that a minimalist feel would be most appropriate for the artists portfolio. Wanting it to have a sleek and clean design, I wanted a simple floating navigation bar as well as opting for the artists name- Daniel Harman, to serve as the link to the landing page. 
It was essential that high quality images that were not warped and are of an adequate size to depict the details within the work were used for the site. 
I utilized Colorhunt.co to find a colour palette for the site, wanting the site to have a  warming aesthetic whilst requiring a neutrality so as not to take away from the images of the artists work. 

#### Features 
Navigation Bar essential for each page, consistent in style, layout and size. The navigation bar linking the user back to the landing page through the artists name, negating the need to make use of the back button. 
The main landing image, introducing the artist style. Followed by a gallery selection of images to demonstrate the artists range. This further extending the range of the visitors scope from the variety of choice.  
Exhibition section on the About Page, bring a the history and future of the artist, whilst including a photograph of the artists, Daniel Harman to fully introduce him to the viewer. 
The footer section, inclusive of a social media link, to explore the artists work during it’s development. 
A Contact Page, containing a contact form, with the text area input set to required so that additional information for the visitors’ inquiries are essential. 

#### Possible Future Features 
-	A artwork purchasing page work on the website.
-	Developing a logo in future.
-	Expanding the social media links and presence. 

#### Screenshots of site pages

<img src="./Readme-media/screenshot-fixed-danielharman-portfolio.png" width="200px" height="auto">
<img src="./Readme-media/screenshot-danielharman-contact.png" width="200px" height="auto">
<img src="./Readme-media/screenshot-danielharman-about.png" width= "200px" height="auto">
<img src="./Readme-media/screenshot-danielharman-projectone.png" width= "200px" height="auto">
<img src="./Readme-media/screenshot-danielharman-projecttwo.png" width= "200px" height="auto">
<img src="./Readme-media/screenshot-fixed-danielharman-projectthree.png" width= "200px" height="auto">
<img src="./Readme-media/screenshot-danielharman-projectfour.png" width= "200px" height="auto">

 
#### Technologies

- Visual Studio Code 
- Github 
- Git
- HTML 
- CSS 
- Bootstrap V5.3.x 
- W3C HTML & CSS validator.  
- Tinypng.com 
- Beautifier. 
- Unsplash.com
- Pexels.com
- imagecompressor.com
- ChatGPT
- Colorhunt.co
- Dev Tools

#### Testing 
The site was put through W3C HTML & CSS validator.   
I acquired user testing for the site. 
The site was tested on various screen sizes through Dev Tools to ensure website responsiveness across a variety of.   

I utilsed Chrome Dev Tools Lighthouse to test the Performance, Best Practices, Accessibilty and SEO of the site.
<img src="./Readme-media/mobile-lighthouse.jpg" width="200px" height="auto" alt="screenshot of lighthouse test results.">

<img src="./Readme-media/desktop-lighthouse.jpg" width="200px" height="auto" alt="screenshot of lighthouse test results.">

Lighthouse provided suggestions on how to improve the performance, such as specifying the height and width of images within html. As well as the reduction of image size to increase performance. 

<img src="./Readme-media/lighthouse-suggestions.jpg" width="200px" height="auto" alt="screenshot of lighthouse test results.">



#### Manual Testing

| Test Description | Outcome | Status |
|---  | --- | --- | 
| Testing the anchored images on the landing page | Anchored images take you to the correct page | Passed| 
| Testing the social media icon | Clicking the social media icon takes you to a new window | Passed |
| Testing the contact form submission | Resulting in the information being sent to the code institute form dump | Passed |
| Testing that the additional information was required within the form | The form will not submit without all information filled out | Passed |
| All links in the navigation work and linked to the correct pages | The links will take you to the correct pages | Passed |
| Testing the navigation works on all pages | The navigation works the same on all pages of the site | Passed |
| Checking the images are not stretched or pixelated larger screens | Images will resize to larger screens without stretching or becoming pixelated | Passed |
| Testing that the video plays and has controls | The video plays correctly and has controls | Passed | 
| Testing all pages load without errors | All pages load properly | Passed |
 

#### Bugs and Fixes
A issue that I encountered was  the renaming of my files in keeping with industry standard.  Requiring a change in my git config settings to stop being case insensitive as it was preventing the renaming of the files.
In running the site code through the validator, it illustrated several issues with my code. Mainly being the issues with regards to my file paths, from the use of invalid characters. I was able to fix this and restore the images to the code. I unfortunately found several floating <div> tags within the code left over from development, I was able to locate and fix.
My site did not pass the css validation initially, due to a value error. I corrected the issue and my css passed the validation. 

Another bug that I encountered was the body container hugging the left of the screen on the index page and the project-three-page. I was able to find that on the index page I had implemented the container class in the wrong tag and on project-three-page I had not included the container class which would fix the layout issue to centralise the page body. 

Putting the site through the valiidator also found that on the about.page, I had miss labeled an aria-label and had not assigned the height to the video tag properly. I fix --------


<img src="./Readme-media/testing-contact-form-form-dumb.png" width="200px" height="auto" alt="screenshot of working contact form, resulting being taken to form dump.">

<img src="./Readme-media/css-fail-validation.png" width="200px" height="auto" alt="screenshot of css failing validation">
<img src="./Readme-media/css-validator-pass.png" width="200px" height="auto" alt="Screenshot of css passing validation">

<img src="./Readme-media/validation-fail-about-pg.png" width="200px" height="auto" alt="screenshot of about page failing validation">
<img src="./Readme-media/validation-about-pg-pass.png" width="200px" height="auto" alt="screenshot of about page passing validation">  

<img src="./Readme-media/index-validation.png" width="200px" height="auto" alt="screenshot of index html validation">
<img src="./Readme-media/validation-contact-pg.png" width="200px" height="auto" alt="screenshot of contact page html validation">
<img src="./Readme-media/project-one-validation.png" width="200px" height="auto" alt="screenshot of project one html validation">
<img src="./Readme-media/project-two-validation.png" width="200px" height="auto" alt="screenshot of project two html validation">
<img src="./Readme-media/project-three-validation.png" width="200px" height="auto" alt="screenshot of project three html validation">
<img src="./Readme-media/project-four-validation.png" width="200px" height="auto" alt="screenshot of project four html validation">




#### Deployment
The site was deployed to Github Pages from its [GitHub Repository](https://github.com/sims-bit/Milestone-Project-One.github.io.git), the steps are as follows:
- Log into Github
- Navigate to the to the settings tab from the Github repository.
- From the source dropdown menu select the Main branch and then save.
- The page will refresh automatically with successful deployment it will take a few moments.
- Within Github scroll back down to Github Pages and you will be able to find the link to the deployed website.


See live site [here](https://sims-bit.github.io/Milestone-Project-One.github.io/). 

### Local Deployment

Cloning the project from Github:
- Within the [GitHub Repository](https://github.com/sims-bit/Milestone-Project-One.github.io.git) under the repository name select "Clone or Download"
- Within the Clone with the HTTPs section, copy the repository URL.
- Open Gitbash
- Change the current directory to where you want the clone directory to be.
- Type git clone, then paste the URL you copied earlier.

- With making changes to the website, update the code as needed.
- Open a new terminal and add- git add. 
- Add- git commit -m "description of your update"
- Add- git push


I used Visual Studio Code to write my code and I used the terminal to commit and push my code. I also used Github Desktop to push code to Github. Using the terminal to create my commits after making any changes or additions. 
After creating a GitHub repository, Going on to deploy my site to GitHub, by following the guidance document. On Github, under Source, I changed the branch to Master for the branch I'm using. To get the link for my site I had to go to github pages.



#### Browser Compatibility
I have tested my site on the following: 
-	Firefox and Microsoft edge (desktop only)
-	Chrome (desktop and mobile)


#### Credits/ Attributes 
The general text of the website was generated through ChatGPT. 
The Instagram icon in the footer was generated through Bootstrap.  I also utilized Bootstrap for grid layout and responsive design. 
The media from the site were taken from Unsplash.com and pexels.com. With the images being compressed using tinypng.com and imagecompressor.com. 
Colorhunt.co to choose a colour palette. 
My mentor provided me with the ‘https://formdump.codeinstitute.net’ for my form to be actioned too. 
I utilized www.w3schools.com and developer.mozilla.org/en-US/ for referencing. 


