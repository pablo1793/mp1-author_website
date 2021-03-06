# Guy Scriblin

## Fantasy Fiction Author

[View deployed site here](https://pablo1793.github.io/mp1-author_website/)

A comprehensive website for a fantasy author based in the south-west of Ireland. Website features a landing page, a news page containing progress bars that inform of his forthcoming publications and how near they are to being finished, and a section featuring his latest published novel. There is also an online library containing all of the novels published by the author so far, along with their synopses; and an about page informing about the author's biography. Additionally, a form to sign up to the author's monthly email newsletter can be accessed on any page via a button on the navbar.

The primary goal of the website is to engage prior and new readers alike, providing them with information on future projects, published works, and the author himself all in one place.

<img src="./assets/images/landingpage-screencap.min.jpg" alt="Landing page screen capture">

The business goals of this website are:
* Build brand awareness.
* Host an enjoyable space for newcomers and old hats alike.
* Create interest in forthcoming projects.
* Provide images of published novels and brief synopses to capture user's curiosity.
* Ultimately sell more books.

The customer goals of this website are: 
* Following the authors progress on projects they are looking forward to reading upon publication.
* If unfamiliar with the author, getting a good idea of what his books are about.
* Learning more about stories that interest them.

## UX

#### Ideal user

##### The ideal user for this website is:
* English speaking.
* Interested in fiction, specifically Fantasy fiction.
* Is in their late teens or adulthood.
* Is intrigued by the author's works either from prior or newfound interest.

##### Visitors to this website are searching for:
* Information about the author's projects, both published and yet to be published.
* Information about the author himself.

##### This project is the best way to help them achieve these things because:
* It is the author's official website.
* The website provides destails on all published works so far.
* It also provides data of forthcoming projects, which few other author websites do.

##### Client stories:
1. As a new visitor to the website, I want to easily navigate the site and see if I'm interested in the author's work.
2. As a new visitor to the website, I want to browse the author's bibliography to ascertain whether one of his books might be a good present for my son.
3. As a new visitor to the website, I want to learn a bit about the author because I think we went to school together.
4. As a returning visitor to the website, I want to read through the information provided about his published novels. And see whether I missed any details the first time around.
5. As a returning visitor to the website, I want to sign up to the author's newsletter after seeing a video of him online and finding him interesting.
6. As a returning visitor to the website, I want to keep up to date with the author's progress on forthcoming projects. Which I'm looking forward to reading.
7. As a potential customer, I want to buy the author's first book which was recommended to me. But I am disappointed to find the site doesn't yet have a shop.

## Technologies Used

### Languages Used

* HTML5
* CSS3

### Frameworks, Libraries & Programs Used

1. Bootstrap 4.5.3:
      - Bootstrap was used to assist with the responsiveness and styling of the website.
2. Hover.css:
      - Hover.css was used on the navbar links to enlarge the font-size of said links when hovered over with the cursor.
3. Google Fonts:
      - Google Fonts were used to import the "Ubuntu" font into the style.css file which is used on all pages throughout the project.
4. jQuery:
      - jQuery came with Bootstrap to make the navbar responsive on mobile devices.
5. Git:
      - Git was used for version control by utilizing the Gitpod terminal to commit to Git and push to Github.
6. GitHub:
      - GitHub is used to store the project's code after being push from Git. It also serves as a platform to deploy, clone, and share the project.
7. Gimp 2.10:
      - Gimp was used to create the images of the fictional book covers used in the website.
8. Pexels
      - Pexels was used to source the author portrait for the About page and the background image that features throughout.
9. TinyPNG
      - TinyPNG.com was used to minify all images used on the site to reduce the website's loading time and minimise the user's data usage if not relying
      on a wifi connection.       
10. Balsamiq:
      - Balsamiq was used before beginning to code to create wireframes which served as reference for the design of the website. Although these wireframes 
      do not reflect the final site design exactly, they served as a useful foundation to build on. You can view images of these initial wireframes below.

<img src="./assets/images/landingpage-wireframe.min.png" alt="Landing page wireframe">
<img src="./assets/images/news-wireframe.min.png" alt="News page wireframe">
<img src="./assets/images/library-wireframe.min.png" alt="Online Library page wireframe">
<img src="./assets/images/about-wireframe.min.png" alt="About page wireframe">

## Functionality

### Non-technical

The initial page - or landing page - you will see when visiting the website is little more than a decorated greeting for the user. Containing a title, which is the
author's name, and a subtitle inviting you to explore the website. The background image serves as the backdrop for all pages throughout the site.

At the top of the page is the navbar, which can be found on all pages throughout the website, and remains fixed to the top even when scrolling downwards. It contains six links: one logo -
which is the author's name - that will return you to the landing page if clicked. The first of the four navlinks - Home - shares the same function. The other three navlinks;
News, Online Library, and About, will direct you to the various pages that make up the rest of the website. The final element in the navbar is a button on the right-hand side
labelled "Sign up to the newsletter". When clicked it will open a small, floating window which will request your email address and a password for security purposes.

When visiting the News page you will see two main features. The first a series of progress bars that indicate what projects the author is working on and how close he is to
completing them. The second shows the book cover and synopsis of the author's most recently published novel.

If you click on the Online Library navlink, you can peruse the author's published works. Both book covers and synopses can be viewed and read.

Clicking the final navlink - About - will take you to the author biography page. Here you can view a portrait of the author and read about his life so far.

This is essentially all the functionality available on this site, which you can leaf through on any device. Despite its simple nature, I hope you enjoy browsing it for yourself.

### Technical

This project was written in HTML5 and CSS3. The Bootstrap framework was used for its helpful grid system and the responsive design features it provides. Bootstrap also provided 
the site's only JavaScript feature: which collapses all navlinks into a dropdown button for smaller device sizes. Where they would otherwise clutter the top of the screen.

Although Bootstrap is very useful, original CSS was also written to distinguish the site from a typical website created with the framework. Aspects such as the imagery, font, 
and colour scheme serve this purpose.

At first, the "Sign up to the newsletter" nav element was a simple link. However it was later changed to a button, which opens a modal when clicked. The modal contains a form
which requests the user's email address and password. There is as of yet no backend functionality supporting this sign-up feature.

The contents of the individual pages are organised in rows and columns and contain a small variety of features. Mostly images alonside original text. But also a section on the 
News page containing progress bars. The code for which was taken directly from the Bootstrap documentation, and tweaked somewhat to fit the site's aesthetic.

Finally, at the bottom of all the site's pages there is a simple footer which bookends the design of the website along with the fixed navbar at the top.

### Existing features

* Header Logo. Exists on every page and allows the users to easily recognise the author's brand. When clicked it returns the user to the landing page as they would expect.
* Header Navigation Bar. Exists on every page and allows users to easily navigate the site's pages to quickly get where they want to go.
* Footer Copyright information. Exists on every page and allows the author to protect his copyright.
* Newsletter Signup Button. Exists inside the navigation bar on every page and allows users to sign up to the author's monthly newsletter.
* [News Page](news.html). Allows users to get updated on the author's progress with his ongoing projects and to read about his most recent published novel.
* [Online Library Page](library.html). Allows users to view the book covers and read about all of the authors published novels.
* [About Page](about.html). Allows user to view a portrait of the author as well as read a brief biography detailing his life so far.

### Features to implement in future

* Quotes on landing page praising the author's previously published works.
* Shop Page. Will allow users to buy books directly from the author.
* Characters Page. Will allow users to read more about their favourite characters.
* Author Blog. Will allows users to browse the author's thoughts on a deeper level.
* Option to choose the language of the website. Will allow non-native English speaking readers to also benefit from the information provided by the site.

## Installation Instructions

To clone this project into Gitpod you will need:
1. A Github account. [Create a Github account here](https://github.com/)
2. Use the Chrome browser 

Then follow these steps:
1. Go to [my GitHub profile](https://github.com/pablo1793)
2. Click "Repositories" and choose the repo named "<strong>mp1-author_website</strong>"
3. Click the dropdown labelled "<strong>Code</strong>"
4. To clone the repository using HTTPS, under "Clone with HTTPS", copy the URL link
5. Open terminal
6. Change the current working directory to the location where you want the cloned directory
7. Type "<em>git clone</em>", and then paste the URL you copied earlier
8. Press <strong>Enter</strong> to create your local clone

## Testing + Bugfixes

### HTML Testing

Using the W3C Markup Validator:

* <strong>Landing page</strong> first check reveals an error in the navbar code. A div closing tag is missing. After fixing and upon second validation, <em>no errors or warnings to show</em>.
* <strong>News page</strong> first check reveals same navbar error and a misplaced paragraph closing tag. Fixed navbar issue on all remaining HTML files, and moved closing paragraph tag. Upon 
second validation the paragraph error persists. Next, I removed the paragraph tags completely so the text simply sits within its parent div. Upon third validation, <em>no errors 
or warnings to show</em>.
* Before validating <strong>Library page</strong> I removed the paragraph tags from the rest of texts throughout the website. Upon first validation of the Library page, there are <em>no errors or warnings to show</em>.
* Upon first validation of the <strong>About page</strong>, there are <em>no errors or warnings to show</em>.

### CSS Testing

Using the W3C CSS Validator:

* Upon first validation, <em>multiple parse errors</em> are announced. I think perhaps the comments I was using in my CSS file might be causing this, so I remove all comments.
* Upon second validation, the same problems persist; <em>many parse errors and warnings</em>. However, they all seem to be related to the Bootstrap URI, as I can't see any errors in the CSS that I've written. 
* After some time researching on Google and the Bootstrap documentation, I haven't been able to figure out exactly what the problem is. But it seems solely focused on the CDN URI. So there aren't any changes needed in my CSS, to the best of my knowledge.
* To make sure my CSS was satisfactory, I validated it via <em>direct input</em> and found there to be <em>no errors or warnings to show</em>.

### web.dev Testing

#### Audit results screencaps:

##### Landing Page

<img src="./assets/images/landingpage-webdev-audit1.min.jpg" alt="First Landing Page web.dev Test">

##### News Page

<img src="./assets/images/newspage-webdev-audit1.min.jpg" alt="First News Page web.dev Test">

##### Library Page

<img src="./assets/images/librarypage-webdev-audit1.min.jpg" alt="First Library Page web.dev Test">

##### About Page

<img src="./assets/images/aboutpage-webdev-audit1.min.jpg" alt="First About Page web.dev Test">

#### Audit conclusions:

1. The main issue hindering <strong>Performance</strong> on all pages are render-blocking resources. After some research I have concluded that these resources are in large part CSS and JavaScript components in the Bootstrap library which aren't being used but loaded along with those that are nonetheless when the website is used. As I don't have time to tailor these external libraries myself, for now I have to accept the somewhat hindered Performance.
2. Image sizes also seems to be affecting <strong>Performance</strong>. Observing this I researched which format would work best for this website, and concluded that minified JPEG images would work best. Providing satisfactory image quality, along with the smallest image sizes at my disposal to avoid unnecessary data usage. So I changed all images to that format and ran them through a minifying service before adding them back into the project.
3. Noticing the problems affecting <strong>Search Engine Optimization (SEO)</strong>: lacking meta descriptions and inappropriate font sizes on smaller devices. I promptly added meta descriptions to all pages. And afterwards did a significant restructuring of my websites code to control responsiveness more effectively. After rewriting my HTML to make it more semantically friendly, and reorganizing Bootstrap classes in my HTML, I proceeded to control font sizes and a few other properties on smaller devices via the use of a media query.
4. Further <strong>Performance</strong> issues: "Reduce unused CSS" and "Remove duplicate modules in JavaScript bundles". After going over my style.css file, I didn't find any superfluous - or unused - CSS. So I'm forced to conclude that these issues, like item 1 on this list, pertain to the external Bootstrap and JavaScript libraries I'm using. And as specified before, any editing of those libraries is out of my hands at present.
5. Finally, there is a slight contrast issue affecting <strong>Accesibility</strong>. However its impact is Low. And I am happy with the wesites current design and have decided to not alter the color palette.

### Note on bugfixes

After implementing the changes described in item 3 of the previous Audit conclusions list, another problem was solved. During most of the process of writing the code for this project, I observed an <strong>unintentional spacing</strong> on the right side of all pages. It was most noticeable on smaller screen sizes, but present on every viewport size. This bug can be observed in the screen capture below this final note.

After combing through the code line by line using Chrome Developer Tools, I wasn't certain what was causing the problem, but I was quite sure it was a sizing issue. Generated by my untidy Bootstrap and simplistic HTML. So I proceeded to fix these discrepancies and - as previously mentioned - use a media query to ensure more reliable responsiveness on smaller devices.

To my elation, this general "tidying up" also solved the spacing issue.

<img src="./assets/images/newspage-screencap-bug.min.jpg" alt="News page screen capture">

### Testing client stories from UX section of README.md

1. As a new visitor to the website, I want to easily navigate the site and see if I'm interested in the author's work.
      1. No matter what page the user finds his/herself on, they can easily find and use the navigation bar.
      2. Both the [News](news.html) and [Online Library](library.html) pages contain information concerning the author's work.
      3. The logo in the navigation bar leads the user back to the homepage.
2. As a new visitor to the website, I want to browse the author's bibliography to ascertain whether one of his books might be a good present for my son.
      1. By clicking the Online Library navlink, this user will be directed to the page where he/she can browse the author's published works.
3. As a new visitor to the website, I want to learn a bit about the author because I think we went to school together.
      1. By clicking on the About navlink, this user can read the author's biography which contains information about the author's education.
4. As a returning visitor to the website, I want to read through the information provided about his published novels. And see whether I missed any details the first time around.
      1. On both the [News](news.html) and [Online Library](library.html) pages this user will find information concerning the author's published novels.
5. As a returning visitor to the website, I want to sign up to the author's newsletter after seeing a video of him online and finding him interesting.
      1. No matter what page this user lands on, they can easily find the newsletter signup button nestled on the right-hand side of the header navigation bar.
      2. By providing their email address and password on the corresponding form, they will receive a monthly email with the author's newsletter.
6. As a returning visitor to the website, I want to keep up to date with the author's progress on forthcoming projects. Which I'm looking forward to reading.
      1. On the [News](news.html) page, this user can keep up to date with the author's progress concerning forthcoming porojects with the progress bars feature at the top of the page.
7. As a potential customer, I want to buy the author's first book which was recommended to me. But I am disappointed to find the site doesn't yet have a shop.
      1. Indeed this user is correct. There is not yet functionality supporting book purchasing directly from the website. Although this feature will be implemented soon!

### Manual testing of all element and functionality on every page

#### Home Page

1. Navigation Bar:
      1. Go to the homepage from a desktop.
      2. Change the screen size from desktop to tablet to make sure the navbar is responsive.
      3. When confirming navigation bar responsiveness, check there are no size changes to the menu items that might alter the navbar's aesthetic.
      4. Click on the bavbar logo to verify it links to the landing page.
      5. Click on each of the navigation bar items to ensure they link to the correct page.
      6. Click on the "Sign up to the newsletter" button to ensure modal and form are responsive to the screen size.
      7. Change the screen size from tablet to small to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu in the correct position.
      8. Click the burger icon and verify that the menu drops down and the menu text is centered.
      9. Repeat verification of responsiveness and functionality on my mobile phone.

2. Title and subtitle:
      1. Go to Home page on a desktop and verify positioning and styling of central title and subtitle.
      2. Change screen size from desktop to tablet and repeat verification. 
      3. Repeat verification on my mobile phone.

3. Footer:
      1. Go to Home page on desktop and verify footer's contents are centered and the footer itself is fixed to the bottom of the page.
      2. Reduce and increase the window's size to ensure footer's responsiveness at different sizes.
      3. Check responsiveness of footer by changing screen sizes from desktop to tablet, then from tablet to mobile. Also check on mobile phone.

#### News Page

1. Navigation Bar:
      1. Repeat verification steps taken for the navigation bar on the Home page.
      2. Verify the navbar is identitcal on all pages.

2. Progress Bars:
      1. Verify the "Forthcoming Projects" title and progress bars feature resize in accordance with their media query parameter when screen size is changed to tablet.
      2. Repeat verification for small screen size

3. Latest novel release:
      1. Confirm that book cover image and synopsis text change positioning when screen size is changed from desktop to tablet. From each taking up half the space of their container side-by-side at desktop size, to the book cover moving above the synopsis at tablet size.
      2. Verify the same happens when viewed on a mobile.
      3. Make sure that the text at the top and bottom of the synopsis is centered, while the middle text is pushed to the left.
      4. Verify this is maintained at all screen sizes.
      5. Repeat verification on my mobile phone.

4. Footer:
      1. Repeat verification steps taken for the footer on the Home page.
      2. Verify the footer is identitcal on all pages.

#### Online Library Page

1. Navigation bar: 
      1. Navigation bar code is identical on all HTML pages. Testing already completed.

2. Library items (book covers and synopses):
      1. Repeat the verification steps taken for the "Latest novel release" section on News page for all three novel sections on the Online Library page.
      
3. Footer:
      1. Footer code is identical on all HTML pages. Testing already completed.

#### About Page

1. Navigation bar: 
      1. Navigation bar code is identical on all HTML pages. Testing already completed.

2. About the author section:
      1. Verify the author portrait sits on top of the biography text on desktop, table, a mobile screen sizes.
      2. Check that the text is centered on all screen sizes.

3. Footer:
      1. Footer code is identical on all HTML pages. Testing already completed.

#### Sign Up Modal

1. "Sign up to the newsletter" modal and form:
      1. Verify the modal works correctly on desktop and tablet screen sizes. And that it disappears on mobile screen sizes.
      2. Check that the text is centered. And that placeholder text disappears once something is typed.
      3. Repeat verification on my mobile phone.

## Screenshots

The following are a series of screenshots of the website's final design. Although the background image appears choppy in the screen captures, this is due to the extension used to
take the screenshots. When using the website, the background image is set to fixed and no-repeat.

### Landing Page

<img src="./assets/images/landingpage-screencap.min.jpg" alt="Landing page screen capture">

### Modal

<img src="./assets/images/modal-screencap.min.jpg" alt="Modal feature screen capture">

### News Page

<img src="./assets/images/newspage-screencap.min.jpg" alt="News page screen capture">

### Online Library Page

<img src="./assets/images/librarypage-screencap.min.jpg" alt="Online Library page screen capture">

### About Page

<img src="./assets/images/aboutpage-screencap.min.jpg" alt="About the author page screen capture">

## Credits

### Content

* Book and series titles, all original texts - including book synopses and author bio - are all fictional. Written by me, Pablo Page.

### Media

* Author portrait, background image, and the book cover background images were all sourced from Pexels.
* Book cover background images were edited by me using Gimp to transform them into fictional book covers.

### Documentation

* I read [AJ Greaves's](https://github.com/AJGreaves) README.md file for her [Portrait Artist](https://github.com/AJGreaves/portrait-artist) project at the suggestion of my Mentor, so I could see a good example of a well made documentation. Her clear and detailed README proved very helpful and instructional. Thank you AJ!

### Acknowledgements

* I was inspired to create a website for a fictional author partly because I'm a fan of the fantasy genre. But in larger part because of my great interest in the works of Brandon Sanderson, whose [website](https://www.brandonsanderson.com/) I have frequently visited.
* I would like to thank my mentor Victor, who was very helpful and encouraging throughout the process of doing this project. I'm sure I couldn't have managed to do it without his guidance. 

#### Disclaimer

The content of this Website is purely fictional and for educational purposes only.