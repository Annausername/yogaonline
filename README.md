# Yoga Classes

Online Yoga Classes is a landing page for beginners and rookies who are looking to join online yoga practices. Yoga Classes community offers a wide schedule of online classes with different types of yoga along with teachers.

Users of this website will be able to find all the information they needed to know about Online Yoga Classes: About the mission and the vision of the group of teachers, time schedule, reviews and top classes to start from.

![Responsive Mockup](https://github.com/Annausername/yogaonline/blob/main/media/yoga-online-mockup.png)
Also, the live link to the initial Figma mockup can be found here - https://www.figma.com/file/ImwScB0POYMXE0BAMEhamE/Untitled?node-id=2%3A24

## Features 

- Online Yoga Classes contains of the header with navigation links, footer with social network icons that lead to appropriate netwoks in the new page and a background within all 4 pages.
- Main page has two images with a basic yoga poses, Who We Are section with community mission and vision along with a group photo of teachers. On the bottom of the Home page there are two YouTube videos playing on-site.
- Our Classes page contains an Upcoming Events section with Yoga schedule and a background for this section. Community section contains reviews and a background for this section.
- Join Us page contains a form and an image. Form redirects to a Form Confirmation page after clicking submit button.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Home page, Our Classes and Join Us page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/Annausername/yogaonline/blob/main/media/nav-bar.png)

- __The landing page logo and images__

  - The landing includes a logo, quote and two photographs and introduces the user to Yoga in general with two poses that a user would be doing along throughout the class.

![Landing Page](https://github.com/Annausername/yogaonline/blob/main/media/landing-images.png)

- __Who We Are section__

  - The Who We Are section will allow the user to learn more about the group of teachers introducing their mission and vision. 
  - This user will see who he is going to learn from and what drives these people. This should encourage the user to consider this group of people as his teachers. 

![Who we Are](https://github.com/Annausername/yogaonline/blob/main/media/who-we-are.png)

- __Top Picks__

  - This section contains two videos with links to Youtube (the videos are playing on-site) which are the top picks from the teachers so far. The user can play these videos and get to know the team more as long as the classes he will be joining.
  - This section will be updated as these picks change to keep the user up to date. 

![Meetup Times](https://github.com/Annausername/yogaonline/blob/main/media/top-picks.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Online Yoga Classes. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.

![Footer](https://github.com/Annausername/yogaonline/blob/main/media/footer.png)

- __Upcoming Events__

 - This section will allow the user to see exactly when the yoga classes will happen and what kind of Yoga is available for the user to join at this time.
 - This section will be updated as these times change to keep the user up to date.

![Upcoming Events](https://github.com/Annausername/yogaonline/blob/main/media/events.png)

- __Meet You__

 - This section will allow the user to understand that no matter of the experience level he has he will be able to find the appropriate class.

![We Meet You](https://github.com/Annausername/yogaonline/blob/main/media/we-meet-you.png)

- __Community__

 - This section will allow the user to see the latest students' comments about the classes to understand people's attitudes towards the lessons.

![Community](https://github.com/Annausername/yogaonline/blob/main/media/events.png)

- __The Join Us Page__

  - This page will allow the user to get signed up for Yoga Online Classes to start their journey with the community. The user will be asked to submit their full name and email address. 

![Join Us](https://github.com/Annausername/yogaonline/blob/main/media/join-us.png)

- __Form Confirmation__

  - This page will allow the user to see that he successfully signed up for Yoga Online Classes and is expected to receive a response.

![Form Confirmation](https://github.com/Annausername/yogaonline/blob/main/media/form-confirmation.png)

## Testing 

 - I tested that these pages work in different browsers: Chrome, Firefox and Safari.
 - I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the dev tools device toolbar.

Main images, top picks videos, upcoming events and signup blocks that are inline in the original page size - displayed one above another on the screen sizes with a width from 1000px and down.
Who We Are section is displayed one above another on the screen size width of from 1000px and down. 
The Community section is displayed as one column starting from the screen size width of 1235px and down. 

 - I confirmed that the header, footer and all text are readable and easy to understand.

 - I have confirmed that the form works: requires entries in every field, will only accept an email in the email field,
and the submit button works.

- __Bugs__

Solved bugs

 - Footer was not sticky and would always raise to the middle of the page. I had to use a container "wrapper" with a value of min-height to push the footer down.
- Two main images to display as column in a responsive version with a help of css property "display : contents;".
- Community background image doesn't fit the mobile version, so it was removed from the screen size width of 1235px and down. 
- The Community section was not centered on the screen size width from 1000px to 540px, so it was given a property of "width : fit-content".

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator).
1 Warning occured though with a text "Imported style sheets are not checked in direct input and file upload modes.", however, browsing throught the internet I've found the explanation to the warning on [StackOverflow](https://stackoverflow.com/questions/25946111/importing-css-is-ending-up-with-an-error).

### Unfixed Bugs

- The Upcoming Events section is not centered in mobile version;
- The Community section lacks background on the screen size width of 1235px and down. 
- The image on the Join Us page appears too small on the on the mobile version from a UI/UX standpoint.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://annausername.github.io/yogaonline/index.html

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

## Credits

### Content 

- Some of the text used in the various pages were borrowed and adapted from [DoYogaWithMe](https://www.doyogawithme.com/).
- Videos in the "Our Top Picks" section were borrowed from [Yoga With Adriene](https://www.youtube.com/c/yogawithadriene)
- The icons throughout the whole website were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos and images used for the Online Yoga Classes website page were taken from [Pexels](https://www.pexels.com/) open source.
