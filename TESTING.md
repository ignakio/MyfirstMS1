# 6. Testing


## 6.1 - Validation Testing 

Validation testing was undertaken for HTML and CSS


With these inital results I set about fixing the returning errors. Once this was complete I retested and the following results were returned

<img src="readme_files/readmefilesimgs/htmlvalidator.png" style="margin: 0;">

At this stage I was happy with the HTML Validation as it returned no errors. 


For CSS validation the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used by direct input. It yielded the following results:

<img src="readme_files/readmefilesimgs/cssvalidator.png" style="margin: 0;">

The CSS yielded no errors and I was happy to procede with further testing at this stage. 
<p>&nbsp;</p>

## 6.2 - Lighthouse testing

For some further insight insight I tested the page with [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)


<img src="readme_files/readmefilesimgs/lighthousetesting.png" style="margin:0;">



## 6.3 - Responsiveness and Compatibility

To check responsiveness for the site [Google Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools) were used which provide the following results 

<img src="readme_files/readmefilesimgs/responsivebreak.png" style="margin:0;">

<p>&nbsp;</p>

## 6.4 - Devices and Browsers

I was unable to find a way to test my site on Internet Explorer as I did not have access to it. This is something I hope to rectify and work on after submission. 

The galaxy fold was the only device that had some display issues. The didn't overlay effect the usage of the website. However, I would like to improve it in portrait mode.

<img src="readme_files/readmefilesimgs/devtest.png" style="margin:0;">

<img src="readme_files/readmefilesimgs/brtest.png" style="margin:0;">

<p>&nbsp;</p>

## 6.5 - Code Institute Peer Code Review

I submitted my project for feedback on the Peer code review channel of the Code Institutes Slack. With the feedback I gained from this I was able to implement some fixes and changes.

- The Navbar brand Hover state was forcing the text and navbar to expand. I changed the hover properties for navbar.brand and this stopped the menu from expanding.

- I also changed the display properties for the mailing list to display differently on devices smaller than lg. This dropped it down to it's own section and was more visually appealling. 

- As a result of sharing my project I was also able to figure out something that was broken in the About us section. The About Us text was overfollowing and presnting issues with horizontal scroll. This was due to a spelling error for a Container item. Without the slack channel I may not have spotted this. 

<p>&nbsp;</p>

## 6.6 - Performance Testing 

- Some Additonal performance testing was carried out on [WebPageTest](https://www.webpagetest.org/) with the page scoring very well on every section bar security. This is something I'm sure I will learn to improve on as I progress on the course

<img src="readme_files/readmefilesimgs/webtest.png" style="margin:0;">

<p>&nbsp;</p>

## 6.7 - Further Responsive Testing

Some additonal visual testing was done on the following websites to see how the webpage looked on different devices together.

- [Responsive Design Checker](https://www.responsivedesignchecker.com/)

- [Am I Responsive](http://ami.responsivedesign.is/)

<p>&nbsp;</p>

## 6.8 Testing User Stories. 
<p>&nbsp;</p>

### 6.8.1 - First time user of the site goals

- As a first time user, I want to learn a bit more about the business and what they do?
    - A first time user can achieve this by reading the About Us, linking to the social media accounts in the footer or using the contact form.

- As a first time user, I want to learn about the clients feedback of the business. 
    - The User can do this in the Feedback section or by using the clients feedback.

- As a first time user, I want to learn where the personal trainer is located and what are the opening hours
    - The user can achieve this by hitting the location section in the navbar or by scrolling down the page to it.

- As a first time user, I want to navigate the content and be able to interpret and understand the information easily.
    - The user can achieve this as each section has pictures, icons and limited text to convey the message in an easy manor.

- As a first time user, I want to follow the business on social media and be able to contact them. 
    - The user can achieve this by clicking on the social links in the footer

- As a first time user, I want to be able to check the site on mobile as well as desktop. 
    - The user can achieve this as the site is fully responsive across mobile and desktop. 

### 6.8.2 - Returning user of the site’s goals

- As a returning user, I want to learn more about the coach experience.
    - The user can achieve this by selecting About Us in the Nav Bar or scrolling down the page. 

- As a returning user, I would like to contact the business to get answers to my questions. 
    - The user can achieve this by submitting a message using the contact form. 

- As a returning user, I would like to be able to find a phone number to call the shop to ask them to hold something for me. 
    - The user can achieve this by using the number provide in the Location section.

### 6.8.3 - A frequent user of the site’s goals

- As a frequent user, I want to be able to sign up to the Beelive list.
    - The user can achieve this by signing up in the hero image on large devices or in the sign up box below the hero image on smaller devices

- As a frequent user, I want to be able to find quick links to the company's social media pages. 
    - The user can achieve this with the quick links that are located in the footer. 


## 6.9 Bugs 

- One of the biggest bugs initally was the Heading font of Raleway not displaying in the hero image. This was overcome by using " instead of '. 

- The website was not displaying correctly on iPhone 5/SE.
    - To overcome this problem I added a media query for this device. 

- In the about us section the text was overflowing beyond the container limit I had set. 
    - This took some work to figure out but ended up being down to a mispelt item. Once 'Container' was spelled correctly it worked perfectly.

- The footer was not displaying the social media icons correctly. 
    - This was down to a margin right issue that was pushing the icons incorrectly when resizing the viewport. This was fixed by using display properties and changing the col sizes for social links.

- On the Pixel 2 XL the hero image was taking up too much of the screen.
    - I overcame this by setting a media query to adjust the size of the hero image using viewport width and height.

- The hover state for the navbar was causing the navbar to grow as a user hovered over it.
    - To fix this issue I adjusted the font-size on the hover state and changed the color instead to indicate the hover state. 

[Return to README.md document.](https://github.com/ignakio/MyfirstMS1/blob/master/README.md)