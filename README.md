# Heart Of Vinyl

# About

### Heart of Vinyl is a ficticional charity record shop, that specialises in vinyl trading and donation in-store.
### This charity shop is set to help victims of homophobic abuse, and provides a safe haven for people to meet and share their common interests through vinyl trading, donating and volunteering which also provides a sense of community, as _inclusiveness_ is the **motto** in this establishment.

### Everyone is welcome no matter the age, ethinicity, sexuality or beliefs.

# User Experience (UX)

# Strategy

## User Stories 

### Reasons as to why a user my visit this website

 * They are part of the LGBTQ+ community or an ally
 * Have an interest in becoming more involved with the community
 * Have an interest in vinyls and music
 * Trying to find a safe space to be able to be themselves

 ### Reasons for this website 
 
 * Provide information as to where the user could find this store
 * Offer a chance for anyone to participate in trading vinyls and volunteer by filling up the form
 * Inspire a sense of community by sharing stories and music

 # Scope 

 ### What a user can expect

 * Meaningful content
 * A clean and aestethically pleasing website 
 * Easy to navigate
 * Helpful content 
 * A good image gallery 
 * Contact information 
 * A powerful and meaningful hero image
 * A way to connect with the LGBTQ+ community

 ### What a user may be seeking

 * More information about the Vinyls
 * More information about the LGBTQ+ community 
 * Ways to contact and donate towards a cause
 * A way to volunteer in-store

 ### What I look for as a developer / business

 * Provide a useful and informative website
 * A way to connect the community through music
 * To provide a way for users to be able to get more involved 
 * To be able to raise donations and awareness for the victims of homophobia and other abhorent actions against this group

 # Structure

 ### This website is made up of 3 pages
 * The homepage which consists of: 
   * A navbar with 3 menu options 
   * The hero image with a Jumbotron and clickable button with color changing when hovered over, that links to the Join us page
   * The footer with the contact information, social media links and a small information about donations

 * The Gallery page which consists of:
   * Images about vinyls and LGBTQ+ community 
   * A clean and interactive picture layout due to it's hover animation

 * The Join Us page which consists of: 
   * A form with contact information input and a text box
   * A submit button with a color changing when hovered over

# Skeleton 

## Layout

* For this project I have used Bootstrap to make an entirely responsive website in all devices. <br> I have used containers and bootstrap column system to be able to create an even an responsive grid for the website.
* In the center I implemented another bootstrap feauture which is the Jumbotron, to house information about the website, a "slogan" and the button to redirect to the Join Us form. 
* With the gallery I used one of the bootstrap gallery displays but changed the layout completely, but by using it guaranteed me to have a more even and responsive display on all devices.

* The design of this website was made thinking of mobile first. When tested in different devices, all the content is displayed neatly and aligned. 




# Features

## Existing Features

* Navbar
<img src="images/Navbar-ms1.png">

   * _The Heart Of Vinyl_ navbar contains 3 main links: Home, Gallery and Join US. The navbar is responsive and identical in all 3 pages. 
   For this Navbar the design has been kept simple and tidy in it's appearence. 

* Hero Image
<img src="images/hero-image-ms1.png">

  * The Hero Image has a static image that contains no animation, as it would be distracting and wouldn't fit with the main view of the page. 
  The hero image is trying to reach across the main message on this page, which is inclusiveness in LGBTQ+ community that is also connected throught the love of music. 

* Jumbotron
<img src="images/jumbotron-ms1.png">

    * The Jumbotron layout is kept quite simple and neat. 
    The Jumbotron main function is to briefly explain the purpose of the Website and also extend an invitation for anyone that wishes to join the community, they can do so here through the **Join us** button.

    The Jumbotron also contains one of the very few color item links on the page. 

* Footer
<img src="images/footer-ms1.png">

    * The Footer is consituted by three columns.
    The first column contains the contact info of the store and it's address, by adding the contacts to the footer which is one of the main elements that is consistent in all 3 pages, the user is able to see it at all times, therefore making it easier to find.

    The second column contains all the social links in which the Website is represented. 
    All the icons are grey apart from one as it provides a nice eye catching feature the bottom of the page.
    Besides the single colour icon, each of the social icons have their own colour when hovering over them as well.

    The Third Column is an informative text about Donations to the charity shop. 
    By adding this to the footer it gives it importance but it doesn't make it look like it's the main objective of this charity shop.

* Gallery
<img src="images/gallery-ms1.png">

   * The Gallery is the second page of _The Heart Of Vinyls_ website and it is constituted by the navbar, the footer and a selection of images forming a gallery display. 

   All the images are related to Vinyls themselves or music, and LGBTQ+ Community. 

   To Be able to make this images stand out from just becoming a static gallery, an image zoom animation was added for everytime it's hovered over. 

* Form / Join-Us
<img src="images/form-ms1.png">

  * The Join Us form is the third and final page of the project. 
  In this page the user will be able to join _The Heart Of Vinyl_ community in a more personal way by volunteering in the store by completing the form. 

## Features Left to implement
* Dropdown menu;
* A more detailed about section;
* Wireframes on readme.md
* An Am I Responsive Screenshots (the Am I Responsive website has been having some issues)

# Technologies Used

* This project uses HTML, CSS and Bootstrap.
* The project was developed using Gitpod.
* This project uses GitHub for Storing and Deployment.


# Testing 
|Test Label  | Test Action | Expected Outcome | Test Outcome |
|:--|:--|:--|:--:|
| Navbar | Navigated through all the links in the navbar and clicked on them individually. <br> Clicked on the Jumbotron button to assure that it redirects the user to the Join Us form page |All the links to be responsive and lead to their respective pages. <br> The Join Us button to take the user to the form page | PASS 
|Gallery | Loaded and Refreshed the page, also hovered over the photos to ensure the slow motion transition is in effect and without any errors and issues. <br> Tested the gallery layout on smaller screens using google developer tools to ensure the layout is responsive and keeps a good responsive grid even in smaller screens | The photos should all load fully and when hovered over, and they should also increase in size due to the hover effect. <br> The layout should still keep a neat and tidy shape even when displaying in smaller screens | PASS 
|Join-us Form | Filled the required fields to make sure it displays the "required field" message. Pressed the submit button to ensure that the form gets submited to an external source. <br> Submitted the form to check if the Input names and values display correctly | The required fields should display the correct message, unabling the user from sending any information unless all fields have been filled. The form should submit to an external source. <br> The Input name and values should display when the form is submited | PASS
|Social Media Links | Clicked on all media links to make sure they are responsive and open in a new tab. <br> Hovered over all the social media logos to assure that the hover animation displays correctly | All social media links should open in a new tab and should be responsive when clicked on. <br> All social media logos should transition colour when hovered over | PASS |

## Validator Testing
* CSS
  * No errors were found when testing on the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/)

* HTML

  * No errors were found when testing on the official [W3C Validator](https://validator.w3.org/)

## Browser Compatibility 
 * This website has been tested and verified to work on various browsers such as : Chrome, Firefox and Edge.

## Responsiveness
 * This website has been tested on small, medium and large screens. 
 * When it comes to Xs screens the website has only been tested in the responsive setting on Google Developer tools. 

# Deployment 

* The website was deployed to GitHub pages.
The steps taken were the following:
  
  1. On the prefered Internet Browser, access [Google](https://www.google.com/)
  2. On [Google](https://www.google.com/), type in Github to access the [Github](https://github.com/) page
  3. When accessing [Github](https://github.com/) create an account following the provided steps
  4. After creating an account and profile, create a new/first repository by clicking on "New"
  5. With the new repository now in place the project can now be started
  6. After the project is concluded it is ready for deployment 
  7. For deployment access the settings on the GitHub repository
  8. On the left hand side menu, navigate and select the Master Branch.
  9. Once the master branch is selected, the page will automatically refresh and display a message for the successful deployment.

* For GitHub page live link [Click here!](https://deborasantos28.github.io/milestone-project-1/)
Need to include user stories 

# User Stories
| User Story | Acceptance Criteria |
|--|--| 
| As a member of the LGBTQ+ and a user of this website I would like to know more about this charity.| * Scroll down to the end of the page. <br /> * On the left corner of the footer access the contact details and Address <br /> * Alternatively, contact us directly on social medias and discord chat |
As member of the community and music enthusiast, I would like to be a part of this charity activities. | * On top of the page, navigate throught the menu <br /> * Click on the Join-us option on the menu <br /> * Fill in the required fields on the provided form <br /> * The form and the reasons for wanting to join the charity will be reviewed | 

# Credits

* For the Gallery I used the code from [MDB Bootstrap Static Gallery](https://mdbootstrap.com/docs/standard/extended/gallery/#section-lightbox) for a responsive and simple layout. A few alterations were made to the code along with the customized CSS. 

* For the Media Queries I used the W3Schools example provided. 

* This project was made by using some of Bootstraps code.

* A huge thank you to my family and friends for testing the website and give me feedback that was so valuable when making this project.

## Contents

## Resources 
* Images
  * [Rawpixel](https://www.rawpixel.com) 
  * [Unsplash](https://unsplash.com/)
  * [Pexels](https://www.pexels.com/)
  * [Pixabay](https://pixabay.com/)

* Colour Palette
  
  * [Colorswall](https://colorswall.com/palette/1450/) 
  * [U.S Brand Colors](https://usbrandcolors.com/twitter-colors/)
  * [Brand Palettes](https://brandpalettes.com/instagram-color-codes/)



