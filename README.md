# Balayage Expert London

## Table of Contents
1. [Strategy: The Who and Why](#strategy-the-who-and-why)
2. [Scope: What Features Are Required](#scope-what-features-are-required)
    1. [The Logo](#the-logo)
    2. [The Favicon](#the-favicon)
    3. [The Blogs Page](#the-blogs-page)
    4. [The Sign Up Page](#the-sign-up-page)
    5. [The Footer & Attributions](#the-footer--attributions)
3. [Structure: Shaping The Site](#structure-shaping-the-site)
    1. [Navigation Bar](#navigation-bar)
    2. [The Landing Page](#the-landing-page)
    3. [The About Section](#the-about-section)
    4. [The Services Section](#the-services-section)
4. [Skeleton: The View For The User](#skeleton-the-view-for-the-user)
    1. [Colour Palette](#colour-palette)
    2. [Wireframes](#wireframes)
5. [Testing, Struggles, and Future Features](#testing-struggles-and-future-features)
    1. [Testing](#testing)
    2. [Bugs/Challenges](#bugschallenges)
    3. [Feature Ideas For The Future](#feature-ideas-for-the-future)
6. [Deployment](#deployment)
7. [Development](#development)
8. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)

## Strategy: The Who and Why

On the strategy plane, this project intends to relay information about the hairdressing services 'Balayage Expert London' provides. The main focus is highlights and balayage - though other information; such as price and other services provided can also be found here.

The primary targets of this project are women with long hair looking to change the colour of their hair in the most natural-looking way. Most of which tend to have similar concerns about their hair and questions about the services provided. The website seeks to answer those questions and other hot topics in the form of blogs. So from the perspective of the hairdresser - it is a wonderful tool to document these topics and share with them.

As a client, I would be more trusting of the hairdresser if they wrote about these topics in depth. This would not only set my mind at ease about his/her abilities and knowledge on the topic but also answer any questions/concerns I may have.

In the future more and more blogs would be added to the site and clients would be led here to not only answer them but perhaps also advertise other services that are provided by keeping clients engaged by the way of interesting topics/blogs. As a user of this site, I would sign up for the mailing list to get notified whenever there are any offers or new blogs published.

You can view the deployed website by clicking [**here**](https://destant.github.io/balayage-expert-london/).

## Scope: What Features Are Required


### __The Logo__

![Logo](/documentation/logo.png)

The logo sits on the left-hand side of the sticky navigation bar. This is always in the user's line of sight and builds familiarity with the brand.
  * On larger screen sizes the logo is clickable and takes the user back to the homepage.
  * On smaller screens such as mobiles and tablets this feature is turned off as it can cause misclicks when the 'burger menu' is the intended target click.

### __The Favicon__

![Favicon](/documentation/favicon.png)

Leading on from the logo this feature will also help build familiarity.
* All pages will have the favicon icon in the browser tab - which makes for easy identification of the site when having multiple tabs open.

### __The Blogs Page__

![Blogs Page](/documentation/blogs.png)

The blog page currently includes 6 headings with various topics of interest. This page will likely be used many times by users to refer back to questions that they may have about their hair and other hair-related topics. The page will grow to house many more blogs and users can be pointed toward the page for a more in-depth answer to a question that they may have.
  * In the future when there are too many blogs to scroll through - a search feature can be implemented here.

In its current state the 'blogs' are unclickable and act as a sort of placeholder for future implementation. To not confuse current users with this; a 'coming soon' text is shown when a user's mouse hovers over the individual blog posts. Or in the case of mobiles - it appears when it is tapped.

### __The Sign Up Page__

![Sign Up!](/documentation/sign-up.png)

The 'sign up' section is for users to be able to enter their details (name, surname, and email address) for them to be contacted in the future should any available offers and discounts be coming. It can also notify the users when a new blog post is added to the site.

The industry is known to have weaker months and this feature could be taken advantage of by planning and emailing everyone who is signed up to the site with discount codes and general other offers that would help a salon during quieter periods.

### __The Footer & Attributions__

![The footer and attributions](/documentation/footer.png)

The footer very simply features a clickable Instagram icon that takes the user directly to the 'Balayage Expert London' Instagram profile page.
* Opens in a new tab to help preserve the user's stay on the website for longer.
* Gives users an easy way to access a gallery of sorts and opens up a way of communicating if interested in the services of the hairdresser.

Note: larger screen sizes will also see the attribution link to a leaf vector used within the site. This link is removed for smaller screens as the vector is not in use for them.

## Structure: Shaping The Site

### __Navigation Bar__

The navigation bar is home to the logo and other links that help navigate the website. It gives a clear overview of what you might find when visiting. It changes the way it looks and functions depending on what device they are using. Primarily:
  * devices above a screen width of 1024px
  * and devices below a screen width of 1024px.

**_Larger Devices (screen width > 1024px)_**

![The Navigation Bar](/documentation/nav-bar-large-view.png)

This navigation bar is seen on desktops and other large-screen devices. It features:
  * Sticky - sticks to the top of the page for easy access/navigation from anywhere on the site.
  * Clickable logo - takes the user back to the homepage.
  * Navigation links on the right to various key locations on the website.
  * All clickable links change the cursor look - for easy identification to a user.

**_Smaller Devices (screen width < 1024px)_**

![Small devices Nav-Bar](/documentation/nav-bar-small-view-closed.png)

![Small devices Nav-Bar open](/documentation/nav-bar-small-view-open.png)

This is what a user will see if they are using a mobile device or other small-screen devices such as a tablet. Its features are similar to the full-view Navigation Bar; with some key differences:
  * The 'Burger Menu' - smaller screens benefit from having the navigation links open separately. This allows for a less crammed navigation bar and/or smaller, possibly ineligible, font for the navigation links.
  * Non-clickable logo - whilst okay on tablets, on mobile devices it caused too many misclicks (that were intended for the 'burger menu' instead). Though tablets also benefitted from the extra white space this provided.
  * When open the dropdown list's opacity is lower - for a better user experience overall as the user doesn't lose sight of where they were on the site.

### __The Landing Page__

![The Landing Page](/documentation/am-i-responsive.png)

The landing page is the first thing a user will see and thus has to have the highest impact. Some key things to consider here were:
  * A call to action button - sends the user to Instagram and opens a new chat panel with the 'Balayage Expert London' account.
  * Less is more - lots of 'white space' - didn't want to overwhelm a first-time visitor with too much information immediately.
  * Clear hero image and hero text - Show the user what to likely expect from the website.
    * And if that isn't 100% clear (which is possible!) then the user is greeted with the 'About' section right after.

Picture from [amiresponsive.co.uk](https://amiresponsive.co.uk/)

### __The About Section__

![About Section](/documentation/about.png)

This section is about the hairdresser himself and his experience as a hairdresser. It relays the user with useful information about what he does and what it is he specializes in. It also features a splash of colour to break things up a little with the use of a leaf vector found on [Vecteezy.com](https://www.vecteezy.com/free-vector/leaf-background). This Vector was removed in screen sizes below a width of 1024px due to an overcrowding effect.

The content of this section was written by ChatGPT-3. Below are the steps taken to get there:
  * Step 1 - Tell ChatGPT a backstory so that it may have some context to go on:

![A little backstory](/documentation/chat-gpt-1.png)

![Result!](/documentation/chat-gpt-2.png)

The results here were good but I wondered if I could take things a step further and include elements of 'search engine optimization'. Which is explained below:

  * Step 2 - Do keyword research on Google's [keyword planner](https://ads.google.com/home/tools/keyword-planner/) and prompt ChatGPT with the chosen keywords:
  
![Keywords used](/documentation/chat-gpt-3.png)

The result is what you see in the 'About' section.

### __The Services Section__

![Price list](/documentation/services-price-lists.png)

The services section features a round-up of all services and their respective prices that are offered by 'Balayage Expert London'. This gives the users clear guidance on what services are provided and how much they cost.

On smaller devices the cards are laid out on top of each other due to less space, the users can scroll through the price lists as normal (as seen below).

![Price list mobile view](/documentation/services-small-view.png)

## Skeleton: The View For The User

### __Colour Palette__

![The colour palette](/documentation/colour-palette.png)

The choice of colours is very important, as such, it should be given much thought. Key points to consider when choosing the colour palette:
* Warm tones - this works more harmoniously with natural-looking hair, which is typically warm in tone.
* Not identical colours to colours you would find in hair - some contrast between images used and overall colour scheme is important!
* Colours found in the hair of the hero image on the landing page can be used as a starting place - but ultimately this chosen colour should be replaced to not match exactly (an example of this implementation can be seen above - the chosen colour palette!).

### __Wireframes__

![index.html wireframe](/documentation/wireframe1.png)
![blogs.html wireframe](/documentation/wireframe2.png)
![contact.html wireframe](/documentation/wireframe3.png)

## Testing, Struggles, and Future Features

### __Testing__

__Lighthouse Tests__

![Lighthouse desktop test](/documentation/lighthouse-testing-desktop.png)
![Lighthouse mobile test](/documentation/lighthouse-testing-mobile.png)

* Initially, all images were either .png or .jpg - but the performance was very poor!
* Performance was improved when changing image formats to .avif.
  * Hero-image was changed back to .png because it was the only one to not render properly on an iPhone using safari - all other images were fine as .avif.
* WEBP was also tried but this didn't render at all on chrome - which was reason enough to try something else.

The project was also tested via friends and family; using their native web browsers for responsiveness using these devices/tools:
  * Monitor 25" screen
  * Windows laptop 15" screen
  * iPhone 12 Pro Max
  * OnePlus 8
  * iPad Pro 12.9" screen
  * iPad Pro 11" screen
  * Chrome dev tools for various other options

__Validator Testing__

- HTML - No errors or warnings to show. Link to report [here](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdestant.github.io%2Fbalayage-expert-london%2F).
- CSS - No errors found. Link to report [here](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdestant.github.io%2Fbalayage-expert-london%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).

### __Bugs/Challenges__

__Challenges__

Various smaller bugs and problems occurred throughout the project, which I've learned a lot from! But the biggest challenge I had during the project was by far setting up a carousel effect on the services section. Then, unfortunately, the second biggest problem/challenge I had was taking it away due to it failing W3C validation:

![Initial services design](/documentation/services-price-lists-invalid.png)

* This design was found on YouTube ([link to video](https://www.youtube.com/watch?v=LBAThoUn3rU))
  * The carousel was clickable and looked fantastic, however as previously mentioned it failed W3C validation, so was taken out.
    * I learned that divs cannot be child elements of labels.
    * Possible reimplementation in the future using JavaScript.

__Unfixed Bugs__

As far as I know:
  * The call to action button acts odd on screen sizes that aren't defined specifically in the media queries
    * Most possibly due to the 'position: absolute;' styling.
    * Not sure of a way around it - as different screen sizes have slightly different landing pages.

### __Feature Ideas For The Future__

* A carousel-style price list that passes W3C validation - possibly through the use of JavaScript in the future.
* Clickable blogs - take the user to another page with the desired blog and information.
  * A search function to get to wanted topics faster.
* An API for google reviews to automatically show up and scroll through on a dedicated space on the website.

## Deployment

The project was deployed on GitHub pages from the 'Main Branch Source Code' using the following steps:
* 'git add .', 'git commit" and 'git push' commands were issued one final time when the project was ready and finished.
* On Github the repository for the project was selected.
* Click the 'Settings' tab.
* On the left; select 'Pages'.
* From here; select the source as 'Main Branch'.
* Click 'Save'.

GitHub may take a few minutes to deploy the website so be patient.

The live link to my project can be found [**here**](https://destant.github.io/balayage-expert-london/).

## Development

Should anyone wish to add to the project, please feel free to open a new workspace within its current state; then commit and push any changes to the main branch. I will review and add them to the main branch as soon as possible. Thank you!

Should anyone wish to copy and paste the project - you are also welcome to - please remember to give me some credit!

## Credits 

### __Content__

* The colour palette was chosen by using the [Eye Dropper](https://eyedropper.org/) Chrome extension tool on the hero image, then inserted into [Colormind.io](http://colormind.io/).
* The wireframes were made using [Balsamiq](https://balsamiq.com/wireframes/).
* To help me find and visualize the font I used [Fontjoy](https://fontjoy.com/).
* The 'About' section was written using OpenAI's [ChatGPT](https://openai.com/product/gpt-4).
* [Stack Overflow](https://stackoverflow.com/), [Mozilla Dev Tools](https://developer.mozilla.org), and [CSS Tricks](https://css-tricks.com/) were used a lot to help me build an understanding of the proper use of CSS and general syntax queries I had throughout the project.

### __Media__

* The Logo and Favicon used were made on [Favicon.io](https://favicon.io/).
* Burger Menu and Instagram icons from [Font Awesome](fontawesome.com).
* Leaf Vector from [Vecteezy.com](https://www.vecteezy.com/free-vector/leaf-background).
* To compress .PNG and .JPG files I used [CompressPNG](https://compresspng.com/) and [CompressJPG](https://compressjpeg.com/) respectively.
* All other media and images used are my own.