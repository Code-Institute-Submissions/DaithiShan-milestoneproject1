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

#### Design Choices - Inspirations

The major design inspiration for this website (also listed in credits) is [The Mater Foundation](https://www.materfoundation.ie)
This website is the starting point of a rebuild of that website, which is hosted by an overseas 3rd party on WordPress.

![Mater Foundation Original Home Page](./mater-foundation/assets/images/materfoundation-original.jpg)

The other website that was truly inspirational from amongst a huge group that I reviewed was [the RNLI website - December 2020 View](http://web.archive.org/web/20201220014805/https://rnli.org/)
The visitor draw of a hero image which situates them shoulder-to-shoulder with a frontline worker really impressed me.

![RNLI Home Page Hero Image](./mater-foundation/assets/images/rnli-hero.jpg)

#### Colour Scheme

- The main colours used are shades of orange, grey and white as these are the brand colours of the Mater Foundation

#### Typography
- Roboto is the main body font used throughout the website, with Sans-Serif as the fallback font. It's widely used, and balances professionalism and friendliness.
- Fire Sans is used for titles, and is primarily humanist. This suits a charity's need for warmth, intimacy and friendliness.

#### Imagery
- Every image on the website is from within The Mater Public Hospital, with full rights and consent of use resting with The Mater Foundation.
- Mater specific imagery is very, very important to making sure visitors feel that the site is a window or doorway on to the cause.


### Wireframes

- #### Mobile Home Page Wireframe

![Mobile Home Page Wireframe](./mater-foundation/wireframes/mobile-homepage.jpg)

- #### Tablet Home Page Wireframe

![Tablet Home Page Wireframe](./mater-foundation/wireframes/tablet-homepage.jpg)

- #### Desktop Home Page Wireframe
![Desktop Home Page Wireframe](./mater-foundation/wireframes/desktop-homepage.jpg)


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

    * ![Screenshot of full performance report from Google Chrome Developer Tool Lighthouse.](./mater-foundation/assets/images/lighthouse-report.jpg)   

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

### Bugs Discovered & Resolved

#### Dropdown Box

![Image of first bug, which caused empty box to appear underneath dropdown menu](./mater-foundation/bug-shots/bug-one.jpg)


1. Custom Navbar Dropdown Issues
    * When I first implemented a customized css snippet for my navbar dropdown menu, I noticed that it was generating an additional empty box under right under the parent menu item.
    * To solve the problem of this empty box, I located the point it was being generated (although not the source) and targeted that point with CSS reducing it to null

```
/* Customized CSS Snippet for Navbar from https://inspirationalpixels.com/creating-a-dropdown-menu-with-html-css/ */

.navbar-nav .nav-item ul {
    position: absolute;
    top:100%;
    left:0px;
    padding: 0;
    margin: 0;
    opacity: 100%;
    z-index: 1;
}

.navbar-nav .nav-item ul li {
    margin: 0;
    padding: 0;
    list-style-type: none;
}

/* .customized CSS Snippet from https://inspirationalpixels.com/creating-a-dropdown-menu-with-html-css/*/

/* Additional CSS required to fix bug in that snippet */

div.dropdown-menu.show {
    margin: 0;
    padding: 0;
    border: 0;
}

/* .additional CSS required to fix that snippet bug */

```

2. Custom Modal Issues

![Image of second bug, which caused empty box to appear underneath dropdown menu](./mater-foundation/bug-shots/bug-two.jpg)

    * When I initially tested my custom modal it displayed fine. However, when I tried to enter information into the fields, I couldn't click on it. In fact, clicking on it dismissed it.
    * To solve this, I spent ages reading through the potential problems and solutions. But I realized when customizing the snippet I had removed key functionality.

```
<!-- Customized modal from Bootstrap/Whiskey Drop Module -->

    <div class="modal" tabindex="-1" role="dialog" id="newsletter-modal">
        <div class="modal-dialog" role="document">
            <div class="modal-container bg-light">
                <div class="cancel-wrapper">
                  <button type="button" class="close cancel" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                    </button>
                    </div>
                    <form class="newsletter-modal">
                        <div class="modal-heading-wrapper">
                            <h4 class="heading">Newsletter Sign-Up Form</h4>
                        </div>
                        <div class="modal-input">
                            <label class="visually-hidden" for="modal-full-name">Full Name</label>
                            <input type="text" class="form-control" id="modal-full-name" aria-label="full-name"
                                name="modal-full-name" placeholder="Full Name" required>
                        </div>
                        <div class="modal-input">
                            <label class="visually-hidden" for="modal-email">Email address</label>
                            <input type="email" class="form-control" id="modal-email" aria-label="email-address"
                                name="modal-email" placeholder="Email address" required>
                        </div>
                        <button type="submit" class="btn btn--orange" data-dismiss="modal">Submit</button>
                    </form>
                </div>
            </div>
        </div>

    <!-- .customized modal from Bootstrap/Whiskey Drop Module -->

```

The problem with this code is in the 3rd div from top. I had removed the class name "modal-content" and replaced it with "modal-container".
After looking through documentation on Bootstrap, I finally realized this mistake.

3. Button Styled Calls to Action
    * Originally, the button styled calls to action were anchor tags wrapping button tags, rather than pure CSS styled anchor tags
    * This caused display issues on Internet Explorer, and was flagged as an error by W3C HTML Validator
    * I resolved by deleting out the button tags on every page, and using CSS to style the anchor tags appropriately.

4. Image size
    * Originally on generating a Lighthouse report on my deployed page, it returned a performance rating of 30%
    * I had used png files instead of jpg out of concern for image quality
    * However, these files considerable slowed the load time of the website. So I converted all image files except the logo.


## Deployment

This project was developed using GitPod, committed to Git and pushed to GitHub using the built-in function within GitPod

### Deploy this project from its GitHub repository

To deploy this project to GitHub Pages from its [GitHub repository](https://github.com/DaithiShan/milestoneproject1), the following steps were taken:

1. Log into GitHub.
2. From the list of repositories, select **DaithiShan/milestoneproject1**
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to **GitHub Pages** section.
5. Under **Source** click the dropdown menu labelled **None** and select **Master Branch**
6. On selecting Master Branch, the page is automatically refreshed. The website is now deployed.
7. Scroll back down to **GitHub Pages** section to retrieve the link to the deployed website.

### How to run this project locally

To clone this project from GitHub

1. Follow this link to the [Project GitHub repository](https://github.com/DaithiShan/milestoneproject1)
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPS section, copy the clone URL for the repository.
4. In your local IDE open Git Bash.
5. Change the current working directory to the location you want the cloned directory to be made.
6. Type ` git clone ` and then press the URL you copied in Step 3
```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

### Content
* All content was written by the developer in his professional capacity as Community Officer for the Mater Foundation.

### Media
* All images were created by or have been consented for use by the developer in his professional capacity as Community Officer for the Mater Foundation.

## Credits

#### General
    * The Mater Foundation website served as the starting point for my project, as I want to redesign it - [View Site Here](https://www.materfoundation.ie)
    * Bootstrap as a framework was incredibly useful to building this website
    * The Whiskey Drop Section of the Code Institute Bootstrap Module was very helpful to giving me an idea of where to begin writing, and how to begin structuring, my code.

#### Navbar Dropdown
    * I owe inspirationalpixels.com credit for the styling of the dropdown menu. [View Snippet](https://inspirationalpixels.com/creating-a-dropdown-menu-with-html-css)

#### Footer
    * I owe GitHub user kashgiricse credit for the structure of the footer. [View Template] (https://github.com/akashgiricse/templates-using-bootstrap4)

#### Acknowledgements

    * I owe my mentor Allen Varghese a lot of credit for great mentoring, and the discovery of the responsive view Chrome plugin, and cooolor.com for color palettes.
    * I owe the Slack community a great deal of credit also for their responsiveness and willingness to always help with small problems!
