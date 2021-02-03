# The Mater Foundation Website (Reimagined)

## Milestone Project

This is a reimagined website for the Mater Foundation, the official charity of the Mater Public Hospital where I currently work as Community Officer.

**[View the live project here.](https://daithishan.github.io/milestoneproject1/)**

## Project Goals

1. To engage voluntary support for the Mater from first time visitors, by inspiring empathy, action, trust and confidence.

2. To ensure that returning, former volunteers and existing volunteers feel sure that their support has made or is making a difference.

## User Experience (UX)

-  #### First Time Visitor / Potential Volunteer Goals

1. Quickly see how to get involved
2. Or learn more about potential impact of their support
3. Assess whether The Mater Foundation is a reputable charity, worthy of trust

-  #### Returning Visitor / Volunteer Goals

1. Feel that my support has made a genuine difference
2. Get a deeper sense of charity's work and progress to goal
3. Directly hear from patients about the benefit of their support

-  #### Frequent Visitor / Volunteer Goals

1. See continuously updated content in stories and news
2. See a solid plan to completely fulfill charitable mission
3. Join a community that will be a source of meaning in their lives

### User Stories

-   #### As a first time visitor / potential volunteer, I want:

1. Immediately to have a window, or a doorway, on to the hospital / the cause
2. To see a list of ways of getting involved, and pick one that suits
3. To learn more about the people who benefit, and what the charity's done
4. To be assured by items like charity registration numbers and easy contact points

-  #### As a returning visitor / volunteer, I want:

1. To read recent news that makes me confident I helped make a difference
2. To see a timeline of what the charity has achieved, and get a sense of progress
3. To read patient stories from across hospital, the people I'm really trying to help

-  #### As a frequent visitor / volunteer, I want: 

1. To see fresh news and stories, to get a sense of value and progress
2. To view the charity's strategy, so I feel longterm commitment is worthwhile
3. To join the newsletter, or social media, to feel a greater sense of belonging 

### Design

#### Colour Scheme

- The main colours used are shades of orange, grey and white as these are the brand colours of the Mater Foundation

#### Typography
- Roboto is the main body font used throughout the website, with Sans-Serif as the fallback font. It's widely used, and balances professionalism and friendliness.
- Fire Sans is used for titles, and is primarily humanist. This suits a charity's need for warmth, intimacy and friendliness.

#### Imagery
- Every image on the website is from within The Mater Public Hospital, with full rights and consent of use resting with The Mater Foundation.
- Mater specific imagery is very, very important to making sure visitors feel that the site is a window or doorway on to the cause.


### Sitemap and Wireframe

- Mobile Home Page Wireframe - [View](https://github.com/DaithiShan/milestoneproject1/blob/master/mater-foundation/wireframes/mobile-homepage.pdf)

- Tablet Home Page Wireframe - [View](https://github.com/DaithiShan/milestoneproject1/blob/master/mater-foundation/wireframes/tablet-homepage.pdf)

- Desktop Home Page Wireframe - [View](https://github.com/DaithiShan/milestoneproject1/blob/master/mater-foundation/wireframes/desktop-homepage.pdf)


## Features

### General Features

- Responsive on all devices, so users get the best, tailored experience for the specific way they access the website.
- Clearly interactive pages so that users know what actions to take, and how to take them, at every point 

### Button Styled Links

- Page links like Read More and Volunteer are styled as big buttons so users clearly see them, and can easily tap them on mobile devices, to go to the appropriate page.

### Volunteer Form

- The volunteer form allows users to input contact information, and make a selection between different areas of volunteering, so they can note their preference.
- All input fields apart from the checkbox are required, so users can avoid partial, incomplete submission of details.
- The submit button provides user feedback for hover, and click, so they know an action has been taken.

### Newsletter Modal

- The newsletter sign up modal is a quick pop up, allowing the user to input their details, and join our mailing list.
- The submit button provides user feedback for hover, and click, so they know an action has been taken.

### Content Loops

- Each news or patient story is separately hosted but links to another, similar story, so interested users can continue to read clearly communicated content.

### Downloadable Content and External Links

- Downloadable content on the About Us page, and in the footer, opens in a separate tab so the user can read it later at leisure without interrupting their visit.

## Features left to implement

### Donation Functionality

- A donation function is planned for later roll outs. It would work through use of a button styled link and form similar to the existing volunteer functionality would be enabled on the website. This would allow users to support the Mater Foundation through a once off or regular donation.

### Confirmation Emails for Volunteer Sign-Up, Newsletter Sign-Up

- Further to the user feedback elements that exist, a confirmation email feature is planned for later roll outs. It would be linked to submission of both the volunteer form, and the newsletter sign up form, and would trigger an email confirmation to users who've submitted so that they know their submission was received.

## Technologies used

### Languages used

* HTML
* CSS

### Frameworks, Libraries and Programs used

* Bootstrap v5.0.0 beta ; used to help build the core stylings, and assist with responsiveness

* jQUery ; used for the mobile version of the navbar, and for the newsletter sign-up modal

* Google Fonts; used to import 'Fire Sans' for the title font and 'Roboto' for the body font

* Git; used for version control by utilizing the Gitpod terminal to commit to Git, and push to github

* Github; used to store the project code in a repository, and to deploy the page

* Balsamiq; used to create the wireframes during the design process

* Canva; used to format and edit the website images

## Testing

### Validation
* W3C HTML validation
* W3C CSS validation

The developer used W3C HTML validation and W3C CSS validation to help debug, and check the validity of the website's code.

### Responsiveness
* The Google Chrome Responsive Viewer Plugin was used to test responsiveness across a range of devices
    * **[View the plugin here.](https://chrome.google.com/webstore/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb?hl=en)**

### Performance
* Lighthouse from the Google Chrome Developer Tools provided an analysis of the website's performance.
    * This analysis was key in fixing a development issue around the use of pngs over jpgs for many images, detailed in bugs.
    * **[View the report here.](https://github.com/DaithiShan/milestoneproject1/blob/master/mater-foundation/images/lighthouse-report.jpg)**    

### User Stories Testing

Most common path through the existing Mater Foundation website:

* Home > Donate
* Home > Volunteer is the anticipated most common path based on this data.
* Home page therefore has 2 large, colourful call to action buttons to volunteer

The latest news and patient stories part of the website are the second most frequented, and offer 2 calls to action each.

* Home > Patient-1 > Patient-2 > Etc
* Home > Patient-1 > Volunteer

Similarly,

* Home > News-1 > News-2 > News-3 > Etc
* Home > News-1 > Newsletter Sign-Up

### Testing User Stories from UX Section of ReadME

#### First Time Visitor / Potential Volunteer

- As a first time visitor / potential volunteer, I want immediately to have a window or doorway on to the cause.
    * Home hero image opens on to hospital, and text + CTA position user as a potential life-saving hospital worker.

- As a new visitor / potential volunteer, I want to see a list of ways of getting involved.
    * The volunteer form has a dropdown list of different interests to choose from for this user.
    * Additionally, the footer on every page offers opportunity to join newsletter, social media, or email the charity.

- As a new visitor / potential volunteer, I want to learn how people benefit.
    * Every page provides access to multiple stories direct from patients, and news of recent patient care projects

- As a new visitor / potential volunteer, I want to be assured of charity's legitimacy
    * Footer on every page provides charity registration number, and multiple contact points.

#### Returning Visitor / Volunteer

- As a returning visitor / volunteer, I want to read news that makes me confident I made a difference
    * Latest news is accessible on every page, and shows how volunteers have enabled big projects that will make a transformative difference

- As a returning visitor / volunteer, I want to see a timeline of what the charity has achieved and get a sense of progress
    * A timeline of major achievements is accessible on the About page

- As a returning visitor / volunteer, I want to read stories from patients I'm trying to help
    * Patient stories are illustrated by photos of patients themselves, and stories are in direct quotes.
    * Each story is always linked or listed alongside another, to allow user to continue to pursue reading easily.

#### Returning Visitor / Volunteer 

- As a returning visitor / volunteer, I want to read consistently updated news and stories
    * This is a key reason for the size of this M1P, to provide a multiplicity of news (5) and stories (4)

2. To view the charity's strategy, so I feel longterm commitment is worthwhile
    * The About page features a downloadable Mater strategy with objectives benefiting patient outcomes

3. To join the newsletter, or social media, to feel a greater sense of belonging
    * This feature is accessible on every page via the footer, and is positioned in hero element on Latest News section

### Bugs
Display
Dropdown Box
Modal
Button Anchor Tags
File-Names



## Deployment

## Credits

Attribute to each bit of code and images


