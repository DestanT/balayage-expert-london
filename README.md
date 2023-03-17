# Balayage Expert London

This website is intended for information on the services I provide as a hairdresser, the main focus being highlights and balayages. In future updates I would like to include blogs on the most hot topics in the industry and answers to frequently asked questions in the salon.

It's primary target are women with long hair looking to change the colour of their hair in the most natural looking way. Moreover it can be used to give clients a more in depth answer to the questions that they may have about the services hairdressers provide.

You can view the website by clicking [**here**](https://destant.github.io/balayage-expert-london/).

## Features 

### Existing Features

__Colour Palette__

![The colour palette](/documentation/colour-palette.png)

The choice of colours is very important, as such, it should be the first aspect of the project you look into. Key points to consider when choosing the colour palette:
* Warm tones - this works more harmoniously with natural looking hair, which is typically warm in tone.
* Not identical colours to colours you would find in hair - some contrast between images used and overall colour scheme is important!
* Colours found in the hair of the hero image on the landing page can be used as a starting place - but ultimately this chosen colour should be replaced to not match exactly.

__The Favicon__

![Favicon](/documentation/favicon.png)

* All pages feature the favicon icon in the browser tab - for easy identification of the site when having multiple tabs open.

__The Logo__

![Logo](/documentation/logo.png)

The logo sits on the left hand side of the sticky navigation bar. Thus is always in the users line of site and builds familiarity.
  * On larger screen sizes the logo is clickable and takes the user back to the homepage.
  * On smaller screens such as mobiles and tablets this feature is turned off as it can cause misclicks when the 'burger menu' is the intended target click.

__Navigation Bar__

The navigation bar is home to the logo and other links that help navigate the website. It gives a clear overview on what you might find when visiting. It changes the way it looks and functions depending on what device they are using. Primarily:
  * devices below a screen width of 1024px
  * and devices above a screen width of 1024px

__Larger Devices__

![The Navigation Bar](/documentation/nav-bar-large-view.png)

This navigation bar is seen on desktops and other large screen devices. It features:
  * Sticky - sticks to the top of the page for easy access/navigation from anywhere on the site.
  * Clickable logo - takes the user back to the homepage.
  * Navigation links on the right to various key locations on the website.

![Small devices Nav-Bar](/documentation/nav-bar-small-view-closed.png)

This is what a user will see if they are using a mobile device or other small screen device such as a tablet. Its features are similar to the full view Navigation Bar; with some key differences:
  * The 'Burger Menu' - smaller screens benefit from having the navigation links open separatly. This allows for a less crammed navigation bar and/or smaller, possibly ineligible, font for the navigation links.
  * Non-clickable logo - whilst okay on tablets, on mobile devices it caused too many misclicks (that were intended for the 'burger menu' instead). Though, tablets also benefitted from the extra white space this provided.
  * When open the dropdown list's opacity is lower - for a better user experience overall as the user doesn't lose sight of where they were on the site.

![Small devices Nav-Bar open](/documentation/nav-bar-small-view-open.png)

__The Landing Page__

![The Landing Page](/documentation/am-i-responsive.png)

The landing page is the first thing a user will see and thus has to have the highest impact. Some key things to consider here were:
  * Less is more - lots of 'white space' - didn't want to overwhelm a first time visitor with too much information immediately
    * I used contrasting colours to section off various areas to give a clear outline of the website.
  * Clear hero image - Show the user what to likely expect from the website
    * And if that isn't 100% clear (which is possible!) then the user is greeted with the 'About' section right after.

__The About Section__

![About Section](/documentation/about.png)

This section talks a little about me and my experience as a hairdresser. It relays the user with useful information about what I do and what it is I specialise in. It also features a splash of colour to break things up a little with the use of a leaf vector found on [Vecteezy.com](https://www.vecteezy.com/free-vector/leaf-background). This Vector was removed in screen sizes below a width of 1024px due to an overcrowding effect.

The content of this section was written by ChatGPT-3. Below are the steps taken to get there:
  * Step 1 - Tell ChatGPT a little about yourself:

![A little backstory](/documentation/chat-gpt-1.png)

![Result!](/documentation/chat-gpt-2.png)

The results here were good but I wondered if I could take things a step further and include elements of 'search engine optimisation'. Which is explained below:

  * Step 2 - Do keyword research on Google's [keyword planner](https://ads.google.com/home/tools/keyword-planner/) and prompt ChatGPT with the chosen keywords:
  
![Keywords used](/documentation/chat-gpt-3.png)

The results are what you see used in the 'About' section.

__The Services Section__

![Price list](/documentation/services-price-lists.png)

The services section features a round up of all services offered by myself and their corresponding prices. This gives the user clear guidance on what services are provided and how much they cost. The individual cards for 'Colours', 'Ladies' and 'Treatments' are clickable to be able to scroll through them. This feature is just for style and adds a touch of professionalism to the site.

Unfortunately this feature was taken out for smaller devices due smaller screen space. The smaller screens made it very difficult to look and function correctly without decreasing font sizes to undesirable levels. In turn the price lists were set up on top of each other for easier viewing (as seen below).

![Price list mobile view](/documentation/services-small-view.png)

__The Blogs Page__

![Blogs Page](/documentation/blogs.png)

The blogs page currently includes 6 headings with various topics of interest. This page will likely be used many times by users to reference back to questions that they may have about their hair and other hair related topics. The page will grow to house many more blogs and users can be pointed towards the page for a more in depth answer to a question that they may have.

In its current state the 'blogs' are unclickable and act as a sort of placeholder for future implementation. To not confuse current users with this a 'coming soon' text is implemented when their mouse hovers over the individual blog posts.

__The Sign Up Page__

![Sign Up!](/documentation/sign-up.png)

The sign up section is for users to be able to enter their details (name, surname and email address) in order for them to be contacted in future should there be any available offers and discounts coming up. The industry is known to have 'weaker' months and this feature could be taken advantage of by planning ahead and emailing everyone who is signed up to site with discount codes and general other offers that would help a salon during quieter periods.

__The Footer & Attributions__

![The footer and attributions](/documentation/footer.png)

The footer very simply features a clickable Instagram icon that takes the user directly to my Instagram profile page. It open in a new tab as to preserve the user's stay on the website for longer.

Larger screen sizes will also see the attribution link to the leaf vector used. This link is removed for smaller screens as the vector is not in use in them.

### Features Left to Implement

- A clickable 'Chat to me' button on the landing page; under the hero text - that opens a chat in Instagram and connects you directly to me.
  - The same button made available for smaller screens - but overlapping the hero image.
- Clickable blogs that take the user to another page with the desired blog and information.
- An API for google reviews to automatically show up and scroll through on a dedicated space on the website.

## Testing 

- What testing was done? Does it work?
- How does it look and work on different browsers and screen sizes?
- Mention bugs/problems.

### Validator Testing 

- HTML - Use W3C Validator
- CSS - Use W3C CSS Validator (Jigsaw)

### Unfixed Bugs

- Mention any unfixed bugs and why. Not understanding/not having enough time isn't an excuse!

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

Should anyone wish to add to the project, please feel free to open a new workspace with in its current state; then commit and push any changes to the main branch. I will review and add the to the main branch as soon as possible.

## Credits 

### Content

* The colour palette was chosen by using the [Eye Dropper](https://eyedropper.org/) Chrome extension tool on the hero image, then inserted into [Colormind.io](http://colormind.io/).
* To help me find and visualise font I used [Fontjoy](https://fontjoy.com/).
* 'About' section was written using OpenAI's [ChatGPT](https://openai.com/product/gpt-4).
* [Stack Overflow](https://stackoverflow.com/), [Mozilla Dev Tools](https://developer.mozilla.org) and [CSS-Tricks](https://css-tricks.com/) was used a lot to help me build an understanding on the proper use of CSS and general syntax queries I had throughout the project.

### Media

* The Logo and Favicon used were made on [Favicon.io](https://favicon.io/).
* Burger Menu and Instagram icons from [Font Awesome](fontawesome.com).
* Leaf Vector from [Vecteezy.com](https://www.vecteezy.com/free-vector/leaf-background).
* To compress .PNG and .JPG files I used [CompressPNG](https://compresspng.com/) and [CompressJPG](https://compressjpeg.com/) respectively.
* All other media and images used are my own.