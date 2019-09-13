
![](https://cdn.shopify.com/s/files/1/0259/4160/6479/t/2/assets/logo.png)


## DAO Traditional Chinese Medicine

## Introduction
<hr>

Caitriona O'Neill is a recently qualified Chinese Medicine practitioner and the name of her practice is DAO Chinese Medicine. The business is currently promoted online through a Facebook page. Caitriona wanted a web presence and the aim of the project was to create a website that represented the brand she is trying to build. The brand guidelines for design were simplicity, airy and clean. 

The client would like to be able to expand the website to include new pages including a blog, and faq in the future. 


## User Experience
<hr>

This website is for clients who are interested in finding out more about DAO Traditional Chinese Medicine. In the long term Caitriona would like to use the website to turn potential clients who are thinking about TCM into customers who will attend the clinic. TCM is an equivalent to western medicine and used by 40% of the World's population. The target market for the service is therefore broad. 

### User Types and Journey's

#### A. User with condition or interested in improving health
- This user type would like to find out about the treatments available and the price. The user would also like to check the credibility of the owner and be able to contact the practice to find out more or arrange a booking. The landing page has a call to action for users who would like to make an appointment. The treaments available and pricing are also on the main page. Users can find out more about the practitioner in the 'About Us' section. 

#### B. User with no immediate condition who would like to learn more about TCM 
- This user type is at an earlier stage, interested in getting more information about TCM in general. The user can read about the treatments available. At present these sections through the 'read more' button link to content on the website managed by PRTCM, a TCM registration body. In future these will link to content articles in a blog section on the DAO website. In addition the user can find out more about TCM on the 'About Us' page which has text and a video outlining the history of TCM.


## Features
<hr>

### Existing Features

#### Home page

- Hero image call to action - callout that allows users to get in touch with the practice.
- Explainer - gives a brief summary of the practices approach to wellbeing.
- Treatments - shows users which treatments are available and links to additional information.
- Pricing - informs the user of the prices of services in a way that is clear and easy to understand.

#### About page

- Paragraph about the owner - helps create trust, informs user of practitioners qualifications and registration details.
- Video - links to a video which outlines the history of TCM. 

#### Contact page

- Contact form - allows the user to contact the practice. 

#### Footer 

- Links -  social links helps users find more content about the practice. Legal links outline privacy policy, terms and conditions. 

- Privacy Policy / Terms and Conditions Modal - a bootstrap pop up modal was used to show the user information about privacy and terms and conditions. 


### Features left to implement 

- FAQ - an faq section will allow users to find out the answers to the most commonnly asked questions. 
- Blog - the owner writes articles about Wellbeing and would like to post this content on the website in the future. 
- Corporate page - the owner would like to add a page targeting corporate users who would like to hire the service for employees. 
- Appointment Scheduler - at some point in the future the owner would like to add the facility for users to book directly from the website.

## Technologies Used
<hr>

- HTML
- CSS
- [Bootstrap 4.3.1](https://getbootstrap.com/) - used as the responsive framework.
- [Google Fonts](https://fonts.google.com/) - used for the large selection of free fonts it offers.


## Testing
<hr>

### Code Validation 


The following websites were used to validate the code. 

HTML - https://validator.w3.org/ - This validator checks the markup validity of Web documents in HTML.

CSS - https://jigsaw.w3.org/css-validator/ - This validator compares your style sheets to the CSS specifications, helping you find errors, typos, or incorrect uses of CSS, it will also tell you when your CSS poses some risks in terms of usability.


### User Story Testing 


#### A. User with condition or interested in improving health
- This user type would like to find out about the treatments available and the price. The user would also like to check the credibility of the owner and be able to contact the practice to find out more or arrange a booking. The landing page has a call to action for users who would like to make an appointment. The treaments available and pricing are also on the main page. Users can find out more about the practitioner in the 'About Us' section. 

#### Test and Result 
I tested the above scenarios myself and also asked friends to test it. The landing page has a clear call to action and the 'book appointment' button brings the user to the contact page. The user can navigate to the treatments and pricing section. Users can easily navigate to the 'About Us' page where information about the owner and the practice is available. All links and buttons were tested. 


#### B. User with no immediate condition who would like to learn more about TCM 
- This user type is at an earlier stage, interested in getting more information about TCM in general. The user can read about the treatments available. At present these link to content on the website managed by TCM registration body. In future these will link to content articles in a blog section. In addition this user can find out more about TCM on the 'About Us' page which has a video outlining the history of TCM.


#### Tests and Result 

The external links to additional content from the 'Treatments' section are working and open in a blank tab. The user can naviagte to the 'About Us' page where more information about TCM is available in text and video format. The youtube video is embeedded and works as it should. 


#### Action - Book Appointment 

1. User lands on the 'home' page and the call to action is clearly visiible. 
2. User click the 'Book Appointment' button and is taken to the contact form. 
3. User needs to fill out the fields in order to submit the form. 
4. User can navigate back to the 'home' page or to the 'about us' page. 
5. Contact link is also visible on the Footer. 


#### Action - Find out more information about TCM

1. User lands on the 'home' page.
2. User can scroll to the next section which outlines the approach DAO take to TCM.
3. User can navigate to the Treatments section where information is available about the treatments offered. 
4. User can access additional content by clicking on the 'read more' button. 
5. Social icons are visible on the footer which link to further content. 


#### Action - Check Credibility / Qualifications

1. User lands on 'home' page.
2. 'About us' link is clearly visible in the navigation bar.
3. User navigates to the 'About us' page.
4. User can access information about the owner. 
5. Links to Privacy and Terms and Conditions policies are visible in the footer. These open as a modal on the page. 

### Screen Sizes and Browsers

The website was viewed on a number of devices using Chrome developer tools. The website was also viewed on personal phones and tablets. In all cases the website is responsive and the section and their content is presented clearly.  

A free version of Browserstack was used to test the webpages on the main browsers. 

### Bugs 

-  There was some additional padding visible on all screen sizes which was rectified by setting .row margin to zero. 
- I had some challenges aligning the three sections of the bootom footer on medium size screen (IPAD).This was resolved with some padding-top. 
- Large images were slow to load. The images were optimised which improved load speed. 


## Deployment 
<hr>

### Process used to deploy on GitHUb Pages

1. Select the repository on GitHub shakapoxa/user-centric-project
2. Select settings
3. In the settings sections scroll down the page to GitHub Pages
4. Select Master branch
5. Click save

The site url on GitHub pages is - https://shakapoxa.github.io/usercentric-project/

### Running the code locally / Cloning a repository

1. On GitHub, navigate to the main page of the repository.
2. Under the repository name, click Clone or download.
3. In the Clone with HTTPs section, click the copy icon to copy the clone URL for the repository.
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 2.

``` $ git clone https://github.com/shakapoxa/user-centric-project ```

7. Press Enter. Your local clone will be created.

```
 $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
  >Cloning into `Spoon-Knife`...
  >remote: Counting objects: 10, done. 
  >remote: Compressing objects: 100% (8/8), done. 
  >remove: Total 10 (delta 1), reused 10 (delta 1) 
  >Unpacking objects: 100% (10/10), done 

``` 

## Credits 
<hr>

### Content 

Some text for the 'History of TCM' is copied with permission from the PRTCM Ireland website.


### Media 

The photos from the websites are from Pixabay, Burst and Canva. The video in the 'About us' section is from Unesco.

### Acknowledgements

I would like to thank Caitriona O'Neill for the content, Pat McArt for advice and my mentor Tony Montaro for great suuport. 











