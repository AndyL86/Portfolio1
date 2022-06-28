# **Dark Glass Window Tinting**

Dark Glass Window Tinting is a site that is designed to provide useful information to help people understand the benefits of tinting vehicle windows.
The site is targeted towards potential and existing customers based around the Bradford area who are looking for a professional and established vehicle tinting service. 

## Table of contents
1. [**Planning Stage**](#planning-stage)
1. [**Features Common to all Pages**](#features-common-to-all-pages)
1. [**Features on Individual Pages**](#features-on-individual-pages)
1. [**Future Features to be Added**](#future-features-to-be-added)
1. [**Testing**](#testing)
1. [**Bugs**](#bugs)
1. [**Other Changes**](#other-changes)
1. [**Deployment**](#deployment)
1. [**Technology Used**](#technology-used)
1. [**Credits**](#credits)

## **Planning Stage**

### **Target Audience**
* Users who are looking for a window tinting service around Bradford
* Users who are looking to learn more about window tinting
* Users who are looking to understand the benefits of window tinting

### **Site Aims**
* Educate the user on the legalities of window tinting
* Show the user the various options available for tinting percentages
* Provide the user with information that tells them who Dark Glass tinting are and where to find it
* Give the user an opportunity to contact the business to make an enquiry

### **Color Scheme**
I chose a neutral colour scheme grey colour scheme for the product and contact pages to deliver a sense of prestige in keeping with the company branding (#55525B) and making viewing easy for the user, opting for an off-white/grey text on the product and contact pages (#FAFAFA). For the navigation and footer menus I chose an off-white for the background (#E2E3E4) and a charcoal grey for the text (#46494C). For the header and footer I chose a slightly darker off-white background (#EBEBEB) with a dark grey colour (#3A3A3A) for the menu text and icon colours. I used (https://webaim.org/resources/contrastchecker/) to check the contrasting colors worked well.
 * Main background
 ![Main Background color scheme](docs/read-me/webaim-contrast-checker-pass-body.png)
 * Navigation and Footer
 ![Navigation and Footer](docs/read-me/webaim-contrast-checker-pass-header-footer.png)

## **Features Common to all Pages**
### **Navigation Bar**

![Nav Bar](docs/read-me/nav-bar.png)
 * Located at the top of the page
 * Its partially transparent grey background is designed to give a sense of style and prestige to the brand
 * For ease of navigation as the mouse is hovered over a link, the background is highlighted so the user can see which menu they are selecting
 * As the page size decreases the nav bar is fully responsive and at the mobile level displays as a burger menu
 * As the burger menu icon is selected a block menu appears and the burger menu icon transforms into a menu close X icon
 * The navigation bar is designed to be a non disruptive visually pleasing experience that allows the user to easily and clearly navigate the business website

 ### **Footer**

![Footer](docs/read-me/footer.png)
 * Located at the bottom of the page
 * Its white background is designed to be clear and simple to navigate
 * The footer has links to the Dark Glass Window Tinting social media pages on facebook, instagram and twitter displayed by icons
 * For ease of navigation as the mouse is hovered over an icon, the icon colour changes to lilac so the user can see the icon is being selected
 * As the page size decreases the Social Media icons stay central on the footer

 ## **Features on Individual Pages**
 ### **Product (Home) Page**
 ![Product](docs/read-me/product-page.png)
 * The About Us section will allow the user to understand the varieties of tinting options available and make an informed choice on the level of tint they require
 * It also shows the user the benefits of window tinting
 * As the page size decreases the text area decreases along with the font size. As the page size decreases to fit mobiles the about us and benefits become block and display as a list, making usability on smaller screens easier

### **Gallery Page**
![Gallery](docs/read-me/gallery.png)
* The gallery will provide informative images to the user so they can see examples of previous window tinting applications
* The gallery is valuable as the user can easily identify the quality of work provided by Dark Glass Window Tinting
* The user can visually see the process and finished product provided by Dark Glass Window Tinting
* The page is responsive and is displayed in a grid layout, when scaling to mobile the images stack on top of each other

### **Contact Us Page**
![Contact Us](docs/read-me/contact-us.png)
* This page will allow the user to make an enquiry with Dark Glass Window Tinting
* The user will be asked to submit their First name, Last name, Email address and their enquiry
* This will allow Dark Glass Window Tinting to get in touch with the customer to provide a quotation for their enquiry
* A background image is used behind the form so the user. This image displays the tinting process so the user can understand how the process works
* The page is fully responsive with the form scaling to fit mobile screens

## **Future Features to be Added**
The Dark Glass Window Tinting site is currently at the minimum viable product stage. Future features to be added to increase site usability include:
* 
* 
 * 
 * A news page where bulletins can be posted for upcoming offers and new product releases
 * An affiliate links page to various 

 ## **Testing**
I have tested the site in the Chrome, Firefox and Edge browsers, using dev tools to test responsiveness. I have also asked users to review on mobiles on both Android and IOS and had no issues fed back. 

### **Responsiveness**
![Am I Responsive?](docs/read-me/am-i-responsive.png) 
Whilst the site was designed as Desktop First extensive testing has been done to ensure the site is fully responsive on smaller screens. As well as tesing in dev tools and using various mobile devices I also used (http://ami.responsivedesign.is/) to check for responsiveness. No website breaking issues were found.
As the site changed in size I identified 4 key widths where changes needed to be made.
1. **992px (Laptops)**
  * About US Page
    * Left and right text areas made to take up more page width
    * Middle image pushed to under text areas
  * Club Sessions Page
    * Session times boxes made to be wider so they weren't so squished on the page
  * Footer
    * Footer links centralised to look better on a smaller screen
1. **768px (Tablets)**
  * All Pages
    * Text size reduced to 15px to allow text to fit their areas better whilst still not affecting readability of the site
    * Font size for Nav bar adjusted to stop it breaking at 603px wide
  * Club Sessions Page
    * Session times boxes resized to cover the entire screen to keep boxes well sized and readable
  * Gallery Page
    * Collums reduced from 4 to 3 so images appeared larger on the smaller screen, maintaining useability
1. **600px (Mobiles)**
  * All Pages
    * Hero Image replaced with mobile version. Reducing height and using a smaller version of the original image to decrease loading times as well as take up less screen height space
    * Flukey Feathers logo position changed to be closer to the top left. Also resized image size to a % value rather than fixed allowing it to scale to the page size and not dominate the hero image
    * Navigation Bar changed to display as a block list rather than horizantal to stop it breaking on smaller screens
  * About Us Page
    * Description boxes now display as block rather than side by side and given a width of 90%
    * Why play headers bottom margin also slightly tweaked for mobiles
  * Club Sessions Page
    * Session times boxes now display in a block list and their borders changed to top and bottom rather than each side
  * Gallery Page
    * Collumns reduced to 2
  * Join Us Page
    * Radio inputs set to display block to vertically display
1. **400px (Smaller screens)**
  * About Us Page
    * Images made smaller to fit screen
  * Gallery Page
    * Collums reduced to 1 to maintain decent image size


### **Lighthouse**
![Light House](docs/read-me/lighthouse.png)

All pages have been tested with lighthouse for both mobile and desktop versions, with all pages scoring above 90 for all sections.
Lighthouse was very useful for picking up poor practices and helped with the following: 
1. Accessability
  * Use of aria-labels on links in the navigation bar
  * Highlighting duplicate unique names for labels on the Join Us page which could have confused screen readers
1. Performance
  * Converted all images to webp. Webp is a new image format which is significantly smaller in file size to png and jpg and will be the new standard for images in the future. Before converting my images i checked (https://caniuse.com/webp) for compatability. It is compatable on all browsers expect for IE 11 and is compatable on macOS 11 Big Sur and later. This gave what I felt to be an acceptable level of compatability to warrant its use
  * Resized some images to be smaller so their file size was more acceptable when loading pages
1. SEO
  * Added in more detailed meta tags as well as some missing alt tags on images

  ### **Validators**
![Valid CSS](http://jigsaw.w3.org/css-validator/images/vcss)

  All HTML files were run through (https://validator.w3.org/) and my CSS file was run through (https://jigsaw.w3.org/css-validator/) to ensure all code meets the correct standard. 
  No errors were found, however there were some warnings:
1. gallery.html
 * Warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections. - this is through design choice as the gallery page is consisting of images only 

 ## **Bugs**
There is one know bug on the website. On the gallery page when reducing to 2 collums as the page resizes there is a noticeable amount of white space between the images and the footer. This happens on Chrome and Edge browsers but displays as it should on Firefox. Safari mobile also seems to be unaffected. As a fix, the 2 collums were removed and the site now goes straight to 1 collumn when resizing. The gallery background was also change on 1 collumn to the same as the footer to hide the 1 pixel gap that was created and make the transition from gallery pictures to footer seemless

![Gallery Bug](docs/read-me/gallery-bug.png)

## **Other Changes**
I removed all \<hr\> tags from the site and replaced them with \<div\>, setting a style in CSS to create the same effect. This is because \<hr\> is now defined in semantic terms, rather than presentational terms. For my site I use \<hr\> as presentational only

## **Deployment**
I deployed the website on GitHub pages via the following:

1. From the projects repository go to the **settings** tab
1. On the left hand menu near the bottom click on the **pages** link
1. Under **Source** click on the button "None" which will produce a drop down
1. Click on **Main** and then click **Save**
1. The following message will appear:  **Your site is ready to be published**
1. After a few minutes the site will be published and the message will change to **Your site is published**

You can access the live site via the following link [Flukey Feathers Badminton Club](https://gibbo101.github.io/flukey-feathers-badminton/)

## **Technology Used**
Flukey Feathers was built using HTML5 and CSS3

## **Credits**

### **Content**
* [Flukey Feathers](https://flukeyfeathers.co.uk/) all information on the website is in relation to Flukey Feathers badminton club and was used with their permission
* The text in the **Why Play Badminton?** section on the about us page was taken from [everyone active](https://www.everyoneactive.com/content-hub/activities/9-reasons-to-try-badminton/)
* The project was influenced by the Code Institutes code along project called Love running and coders coffee house. Whilst I have tried to deviate as much as possible and do my own thing, there may be some similarities in the code.
* For general research when tackling something I required support on I generally relied on W3 Schhols for information
* Icons used are from [Font Awesome](https://fontawesome.com/)

### **Media**
* The hero image and background images were taken from [Pexels](https://www.pexels.com/)
* All other images are property of Flukey Feathers badminton club and was used with their permission

### **Thanks**
 * [Richard Wells](https://github.com/D0nni387) - Code Institute mentor who's advice and guidance supported me in the completion of this project