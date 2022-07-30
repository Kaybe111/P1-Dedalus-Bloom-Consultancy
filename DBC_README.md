# Dedalus & Bloom Consulting

![screenshot LOGO](/assets/images/readme/screenshot-logo.png)

- Link to site [Dedalus&Bloom Consulting](https://kaybe111.github.io/P1-Dedalus-Bloom-Consultancy/)

Dedalus & Bloom Consulting is a fictional business consultancy group created for the purpose of the Portfolio1 project which operates in Europe and offers corporations and SMEs a range of services to optimize processes, manage projects and develop strategy in the areas of supply chain, customer services and fintech/instech solutions. The business model is therefore a traditional consultancy setup.

Premise
I had the idea recently about Dedalus creating wings for he and his son to soar to freedom and thought it would be a cool business idea for a consultancy as that is what they essentially do, that being to bring businesses to the next level. I made the link then to Ulysses as the two main characters are Stephen Dedalus and Leopold Bloom and the book is one of my favourites, so that's the idea for the site and business!

Scenario - B2B consultancy business:
The team of consultants can be contracted on project basis or can be held on retainer to offer a client business the opportunity to work flexibly based on their own demands and plans. The website presents the consultancy and should be attractive to hold the attention of potential B2B clients, offering them tasters and insights of their expertise by detailing some past projects on high level.

![mockups](/assets/images/readme/responsive-mockup-screenshot.png)

# Features

Starting out with the idea of a consultancy I knew there would have to be a strong logo. I found Michroma on Google Fonts and thought this was perfect for the logo and nav bar to give them a very strong identity. I then used Cairo for the main pages content, as I thought it was a good match to the Michroma.

At this stage I also considered the Strategy Plane of UX design.

### Strategy Plane considerations:
- - Target audience = B2B, Corporate website looking to attract clients to contact the business and potentially start projects together
- - Value, Unique Selling Point = Dedalus & Bloom bring Customer Journey mapping to the next level, connecting all business areas to the customer and translating KPI performance into hard revenue
- - Competitors, decision makers = very diverse market with lots of consultancies offering similar services. Uniqueness of service mix combining dashboarding with client business model is offered at competitive price.
- - User needs = Corporate decision makers on level of Board, Purchasing, Product Management and general Management will be looking to quickly be drawn in by attractive presentation, simple bundling and overview of services, drilling quickly from high level to more detailed granularity.

These considerations helped me craft the features required, namely:
- a strong but simple landing page, like Apple keep it simple with an emotive image.
- an overview of the services on offer, speaks for itself.
- sample pricing, very important for B2B customers. Also mentioned is the mandatory 'wiggle room' depending on arrangements. A purchaser or manager will want to know that they can haggle.
- a contact form, also there keeping it really simple with an emotive picture of enthusiastic workers looking forward to meeting/speaking.
- a link to a thank you for supplying the form. A bit tricky since there is no POST server, so I had to fiddle a bit here to get something to work.

## Existing Features

### Logo
I already discussed the logo above, but worth noting is that I gave it a blue underline via a '''div''', which helps to give extra character to the logo and page. This bar also stretches to fill the width of the screen with smaller devices, as the effect of the half-screen bar is lost and it just looks a bit weird.

![screenshot LOGO](/assets/images/readme/screenshot-logo.png)

### Nav Bar

As stated, the nav bar is in Michroma font to keep the character of the logo. It features an underline which denotes the active page, but I also created a '''hover''' effect for mouse-over to make sure the user also was clear about the navigation.

![screenshot NAVBAR](/assets/images/readme/screenshot-navigationbar.png)

### Footer

I wanted the footer to show the social media links as in the Love Running project, but I additionally wanted to include the company address details (fictional natually) and an '''iframe''' for Google Maps. I don't have the knowledge right now to use the API so the link is actually from the Coders Coffeehouse project.

![screenshot FOOTER](/assets/images/readme/screenshot-footer.png)

### About page

I included an image of the Dublin bridge at the financial district, in keeping with the business theme of the site. Also it's a Dublin bridge and many copies of 'Ulysses' by James Joyce have the Haypenny Bridge on them as a known Dublin landmark. I wanted to base the company in Dublin so wanted an image to emote this. Plus an image of a bridge is always a positive in business, where you constantly need to be building bridges. I wanted this strong emotional connection in the potential customer.

- I also borrowed the zoom animation from the Love Running project. I like the effect and to be honest I just wanted to practice with it. It does not detract from the site in my opinion and the movement can maybe help to keep a potential customer reading.

![screenshot ABOUT screen](/assets/images/readme/screenshot-about.png)

### Services page

The services page features an overview of the four main areas of support that the business would offer, which I came up with based on my own business experience. I found appropriate icons from Font Awesome and added those. I also changed the layout for smaller screens using a media query so the content is columnated vertically on larger screens and switches to horizontal text on the smaller ones.

![screenshot SERVICES screen](/assets/images/readme/screenshot-services.png)

### Pricing page

Money, money, money. It's always attractive for a business to have an idea of 'what's all this going to cost me now?' so I wanted to have a page featuring an overview for transparency, which gives a strong sense of expectation and increases the Customer Experience. I also got to use a table so was glad of the practice with it.

![screenshot PRICING screen](/assets/images/readme/screenshot-pricing.png)

### Contact screen

I used a form to make it easier for the customer to reach out and start a conversation. I kept the required contact details to a minimal as this really upsets business customers when they have to waste their time filling in details with the fear that they will just end up on another mailing list somewhere.

To make it a bit more interesting I included an 'Ok to SMS/Whatsapp you?' radio button to attract the customer to an additional channel. I also included a text area for the customer to tell us 'why' they are looking at us. If you can already get the customer enthusiastic about working with you by letting them give some detail already, then you are already in the 'healthy dialogue' zone and you haven't even had to grab a phone or keyboard yet.

I additionally added a photo of some friendly contact personnel here, just to bring in some extra emotion and to vary it up visually, keeping it interesting with some human faces and smiles.

![screenshot CONTACT screen](/assets/images/readme/screenshot-contact.png)

### Thank You link

On the advice of my mentor, I was told that links should all work, including the form. This left me puzzled with my '''form''' as I could not use the post method attribute. I firstly took the one from the Code Institute form validator but then this navigated me away from the site and you had to use the browser 'back' buttons to get back into the site, which apparently is not very good. To get round this I used a '#' mark in the '''method''' attribute, then added an '''onclick''' link to the button which would lead to another html page which is not reachable via the nav bar.

This page is very simple. A sincere thank you message for the customer reaching out, with a commitment to respond. Additionally I included a photo of two people working together on a flow-chart which symbolises cooperation and collaboration, essential to a good working relationship.

![screenshot THANKYOU screen](/assets/images/readme/screenshot-thankyou.png)

## Features left to implement

I had a few from my 'scope plane requirements':

### Scope plane considertions:

#### Needs
- [x] overview of services
- [x] overview of company
- [] overview of projects
- [x] overview of pricing (retainer vs project/programme)
- [x] contacts

#### Content requirements
- [x] text
- [] video
- [x] photos/stills
- [] chat and social media contacts

In essence there are two extra features I would include in future:
- - a page of past partners, projects and testimonials to further add to the credibility of the business and thus increase the likelihood of being contracted.
- - a live chat integrate in the site, but this is beyond the scope of my skills currently and also beyond the budget of Messrs Dedalus and Bloom.

# Testing

![screenshot lighthouse score](/assets/images/readme/screenshot-lighthouse.png)

A Lighthouse test gave a very good score in all areas except performance. I do not have the skills to understand why at this stage.

I tested the site using the Google Chrome tools for different devices:
- Desktop Macbook Air
- iPhone 12
- MotoG4
- iPad Pro

All looked fine and worked.

I tested the site on different browsers and here I ran into problems on one page, the contact.html page. The image worked in Gitpod when testing through port 8000, however when I check the Githubpages link in Safari and Chrome the image is not displayed, just the '''alt''' text. I unfortunately do not have time to fix this.

## Validator Testing

The code for the CSS passed through Jigsaw with no problems after I fixed the first few warnings and errors which cropped up. These are documented in the commits.

The code for the HTML also passed the W3Validator, after some fixes. There is however one point of note, regarding the contact form. Because I tried to include the link out ot the thank you screen via the button '''onclick''', this throws an error in the '''form''' as I had to enter a #-tag in the '''method''' attribute.

## Unfixed bugs

The bug with the image on the contact.html page remains one that needs to be fixed.

# Deployment

![screenshot deployment Githubpages](/assets/images/readme/deployment-screenshot-githubpages.png)

- The site was deployed to GitHub pages. The steps to deploy are as follows:
- - In the GitHub repository, navigate to the Settings tab
- - From the source section drop-down menu, select the Master Branch
- - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

# Credits

I have to thank James Joyce for the characters. The rest of the idea for the site is from my own business background.

## Content

The content for each page was wholly generated by me, the author. As stated this is all based on previous working experience.

## Media

I used the website Pexels for the free images.
- Dublin bridge on ABOUT page was courtesy of 'Luciann Photography'.
- Contact center agents courtesy of Yan Krukov.
- Flowchart collaboration image on ThankYou screen courtesy of Christina Morillo.