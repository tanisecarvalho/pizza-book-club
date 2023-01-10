# Everything is Better With Pizza Book Club 🍕📚

Everything is Better With Pizza Book Club is a site that hopes to connect people in Dublin, Ireland who are passionate about reading and love eating pizza. The book club runs on a montly basis. There is a book selected to each month and the meetings happen at a different pizza place every month. 

Users of this website will find all the information about the club. On the home page we have: About the club, how it works, meetings, contact and follow us. On the 2023 Picks we have a list of all the books planned for 2023. On the Join Us page there is a sign up form. This site is target at people who love reading and share another commom interest: pizza. 🍕

![Am I Responsive?](docs/screenshots/am-i-responsive.JPG)

***

## UI/UX

### Logo

The Logo was created on [Canva](https://www.canva.com/).

![Logo](docs/logo.png)

### Color Scheme

The palette was defined uploading the logo on the [Canva Color Palette Generator](https://www.canva.com/colors/color-palette-generator/)

- #E2DCD8
- #344E55
- #ECC422
- #894E37

![Palette](docs/screenshots/palette.JPG)

***

## Features

- __Navigation__
    - It's on the top of every page. On the left shows the book club logo which is a link to the home page.
    - On the right side we have three other links: Home to the home page, 2023 Picks to the page that contains all the books chosen for 2023, and Join Us the page with the form to sign up for the group.
    - The navigation is the same for every page. The only thing that changes is that the current page is underlined.
    - When the mouse hover on the links, the font size increases and they become underlined.

    ![Navigation](docs/screenshots/navigation.JPG)

- __Landing Page__
    - The landing page includes an image of a book and a pizza slice with a text on the right end corner with the name of the club and some short explanation of what the club is about.

    ![Landing](docs/screenshots/landing.JPG)

- __About Us__
    - The about us section gives an explation about how the club works.
    - It contains five boxes showing the 5 steps to be done to join the club.

    ![About Us](docs/screenshots/about.JPG)

- __Meetings__
    - The meetings sections explains how often meetings occur.
    - It has three images that demonstrating examples of meetings.

    ![Meetings](docs/screenshots/meetings.JPG)

- __Contact__
    - The contact section is divided in two.
    - The first part contains the Contact Us information with phone and email.
    - The second part is Follow Us which contains icons which are links for the club social media: Facebook, Twitter, Instagram and Youtube.

    ![Contact](docs/screenshots/contact.JPG)

- __Footer__
    - The footer is the same for all pages and it is located on the end of all of them.
    - It contains the copyright mark and the name of the club.
    - After that we have information about the developer.
    - In the end we have two icons as links for the developer's GitHub and LinkedIn profiles.

    ![Footer](docs/screenshots/footer.JPG)

- __2023 Picks__
    - This page contains all the books that are going to be read in 2023 by the club.
    - It contains 12 boxes, each representing a month.
    - Every box contain the name of the month, a picture of the book, the name of the book, the author and a button with the link to buy the book on Amazon.
    - The button contains the amazon logo and change colors when the mouse hover it.

    ![2023 Picks](docs/screenshots/picks.JPG)

- __Join Us__
    - The join us page has the form to join the group.
    - The form has three inputs: first name, last name and email.
    - The form also have a submit button.

    ![Join Us](docs/screenshots/join.JPG)

- __Thank You__
    - The thank you page is showed after the form submission. 
    - It has a thank you message and informs the user that the club will contact them shortly and a link to return to the home page.
    - It shows an image of a person eating pizza and reading a book at the same time.

    ![Thank You](docs/screenshots/thank.JPG)

- __404__
    - This page is showed when the user try to access a page that does not exist.
    - It has a message informing that the page was not found and a link to return to the home page.
    - The image below shows pizzas boxes with only one slice of pizza left.

    ![404](docs/screenshots/404.JPG)

***

## Testing

### Responsiveness

- This site was tested on the browsers: Firefox, Chrome and Safari on desktop and it worked.
    - __Chrome__
    ![Home Page on Chrome](docs/screenshots/chrome-home.JPG)
    ![2023 Picks on Chrome](docs/screenshots/chrome-picks.JPG)
    ![Join Us on Chrome](docs/screenshots/chrome-join.JPG)
    - __Safari__
    ![Home Page on Safari](docs/screenshots/safari-home.JPG)
    ![2023 Picks on Safari](docs/screenshots/safari-picks.JPG)
    ![Join Us on Safari](docs/screenshots/safari-join.JPG)
    - __Firefox__
    ![Home Page on Firefox](docs/screenshots/firefox-home.JPG)
    ![2023 Picks on Firefox](docs/screenshots/firefox-picks.JPG)
    ![Join Us on Firefox](docs/screenshots/firefox-join.JPG)

- I tested the responsiveness of this site on devtools and I can confirm it worked for all screen sizes.
    - __iPhone SE - 375 x 667__
        - Home
        <br>
        <img src="docs/screenshots/iphone-home-1.JPG" width="150">
        <img src="docs/screenshots/iphone-home-2.JPG" width="150">
        <img src="docs/screenshots/iphone-home-3.JPG" width="150">
        <img src="docs/screenshots/iphone-home-4.JPG" width="150">
        <img src="docs/screenshots/iphone-home-5.JPG" width="150">
        <br>
        - 2023 Picks
        <br>
        <img src="docs/screenshots/iphone-picks.JPG" width="150">
        - Join Us
        <br>
        <img src="docs/screenshots/iphone-join.JPG" width="150">
    - __iPad Air - 820 x 1180__
        - Home
        <br>
        <img src="docs/screenshots/ipad-home-1.JPG" width="250">
        <img src="docs/screenshots/ipad-home-2.JPG" width="250">
        <br>
        - 2023 Picks
        <br>
        <img src="docs/screenshots/ipad-picks.JPG" width="250">
        - Join Us
        <br>
        <img src="docs/screenshots/ipad-join.JPG" width="250">

- I confirm that all the navigation links, icons with links and buttons are working.
- I can confirm that the form works properly. All the inputs are required, the email is validated and the submit button works.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Ftanisecarvalho.github.io%2Fpizza-book-club%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ftanisecarvalho.github.io%2Fpizza-book-club%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
    - Using Lighthouse on devtools, I can confirm that the colors and fonts chosen are easy to read and accessible.

![Lighthouse](docs/screenshots/lighthouse.JPG)


### Bugs
- __Homepage keeps with an extra margin on the right side.__

    - I had a margin of 2rem on the about-us section that was causing the issue. I commented section by section to see which one was causing the issue. I added a 0 on the margin for the sides.

- __Footer was not sticking to the bottom.__
    
    - I put bottom: 0, but it still was not working. Devtools showed that it would not be changed with a static position. So I changed the footer position to absolute and width to 100% because it change the width to smaller when I changed the position.
    Changing to absolute worked with pages with less content but not with larger content, so I changed to fixed and it worked.
    Fixed did not work with larger contents. I changed the body to min-height: 100vh; display: flex; flex-direction: column; and added flex-grow: 1 to the join-us section which was the only one that the content did not reach the end for the footer to stay in the bottom as suggested here https://stackoverflow.com/questions/34796085/how-to-stick-footer-to-bottom-not-fixed-even-with-scrolling
    
***

## Deployment

### Remote Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - On the left side menu, on the section Code and automation, click on Pages.
  - From the source section drop-down menu, select the Deploy from a branch.
  - From the branch section drop-down menu, select main, right on the side select /root.
  - Once the the branch menus have been selected, github will create the page. It might take a few minutes. Once it is done a link will show up on the top of the page.

The live link can be found here - https://tanisecarvalho.github.io/pizza-book-club/

### Clone/Forking
- To fork this site go to its GitHub repository https://github.com/tanisecarvalho/pizza-book-club
    - On the top right of the page there's a button with the option Fork, click on it.
    - A new page "Create a new fork" will open. If you wish, you can edit the name.
    - In the end of the page click on the button "Create fork".
    - Now you have a copy of the project on your repositories.

### Local Deployment
- This site was developed using Gitpod. To edit your copy on Gitpod you will need to: 
    - On your browser of choice install the gitpod extension/add-on.
    - On GitHub open the project repository you forked before.
    - On the top of the page, over the files, there is a green button on the right side of the page saying "Gitpod". Click it.
    - It will open the Gitpod website. On the first time, you will select to connect with your GitHub account and Authorize gitpod-io. After that you'll be creating an account.
        - It might take a while after that because gitpod will be creating your workspace.
    - After the workspace is loaded, you're able to edit it on Gitpod.
    ***
## Credits

### Content

- The icons were taken from [Font Awesome](https://fontawesome.com/)
- Change the cursor from pointer to hand on the buttons was following the instructions at [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor).

### Media

- Besides the books covers, all the images were taken from [Pexels](https://www.pexels.com/)
    - __Home Page__
        - [Landing Section Background](https://www.pexels.com/photo/photo-of-pizza-near-book-3229356/)
        - Meetings: [Left](https://www.pexels.com/photo/coworkers-having-pizza-for-lunch-at-an-office-6914457/), [Center](https://www.pexels.com/photo/photo-of-people-holding-pizza-3944307/), and [Right](https://www.pexels.com/photo/a-group-of-people-eating-pizza-while-having-conversation-6150520/)
    - __Thank You Page__
        - [Thank You Image](https://www.pexels.com/photo/a-man-eating-pizza-reading-a-book-of-hamlet-9560431/)
    - __404 Page__
        - [404 Image](https://www.pexels.com/photo/boxes-of-pizza-on-picnic-blanket-9353454/)

- __Books Covers__

    The images from the book covers were taken from the following websites:

    - January: [Amazon](https://www.amazon.co.uk/N%C3%B6thin-But-Good-Time-Uncensored/dp/1250195756)
    - February: [Amazon](https://www.amazon.com/Fire-Blood-Thrones-Targaryen-History-ebook/dp/B07C6TBTV3)
    - March: [Kobo](https://www.kobo.com/ie/en/ebook/friends-lovers-and-the-big-terrible-thing-2)
    - April: [Amazon](https://www.amazon.ca/Find-Your-Why-Practical-Discovering/dp/0143111728)
    - May: [Amazon](https://www.amazon.co.uk/Storyteller-Tales-Life-Music/dp/139850372X)
    - June: [Amazon](https://www.amazon.co.uk/AM-Club-Your-Morning-Elevate/dp/1443456624)
    - July: [Amazon](https://www.amazon.co.uk/First-21-York-Times-Bestseller/dp/1408716119)
    - August: [Amazon](https://www.amazon.co.uk/Beautiful-World-Where-Are-internationally/dp/0571365426)
    - September: [Amazon](https://www.amazon.com/Beyond-Wand-Mayhem-Growing-Wizard-ebook/dp/B09ZXMG884)
    - October: [Easons](https://www.easons.com/the-midnight-library-matt-haig-9781786892737)
    - November: [Amazon](https://www.amazon.co.uk/Madly-Deeply-Alan-Rickman-Diaries/dp/1838854797)
    - December: [Goodreads](https://www.goodreads.com/book/show/57425158-the-opposite-of-butterfly-hunting)

***

## Wireframes

### Desktop

![Home](docs/wireframes/01-home.png)

![2023 Picks](docs/wireframes/02-2023-picks.png)

![Join Us](docs/wireframes/03-join-us.png)

![Thank You](docs/wireframes/04-thank-you.png)

![404](docs/wireframes/05-404.png)

### Mobile

![Home](docs/wireframes/06-mobile-home.png)

![Others](docs/wireframes/07-mobile-others.png)

