# Die Antwoord - Unofficial Fan Website

User-Centric Frontend Development Milestone Project

This Website is created for the fans of Die Antwoord group and those interested in Zef Culture and music in general.</br>
This page provides information about the artists, gives samples of the music and video and upcoming tour in USA with links to book tickets as well as Social Media links to follow the group.

This webpage is simple in form and clean.  Highlighting groups image, very bold fonts and images were used.

## UX

### User stories

Viewers of the page will be presented with useful information regarding the group. As well as external link to an article about zef culture.</br>
Also included information about the next Tour that group is heading for with links to book tickets and general information about the concerts.</br>
In addition the above, in the footer section, user can find links to the group Social Media platforms.</br>
As a bonus feature and something that is not very common under each music and video player I have placed a button with downloadable pdf file including the lyrics for the songs, so the user can further immerse themselves in Die Antwoord experience, expanding the understanding of musical and political motives.</br>
All information is easily accessible on my own website or through eternal links.

 
### Strategy
Core focus in the design was to make it as easy as possible to access information about the band and their concerts, listen to their music or watch the video on the site while striving for a simple, elegant and user-friendly design.

### Scope
For those accessing the website, I wanted to provide a general description about the band, but also add an extra feature – external link to the article about Zef culture – and useful information regarding upcoming Tour and links to Social Media Platforms.

### Structure
The home page is very simple with the picture featuring both Artists and navigation bar at the top.</br>
On the second page user can find information about the group (including the link to the Article about them and Zef culture).</br>
On the next section we have 3 spotify players showing some of their most popular songs and the music video truly capturing the essence of this group!</br>
Scrolling down to the next section, the user can see information about the groups next Tour including dates, venues and links to book tickets. Underneath you can see the subscribe form to receive updates surrounding the group.</br>
In the footer section, I have included Social Media icons with links and contact form for the fans that would be willing to contribute to further development of the site.

### Skeleton

#### Desktop
[Home wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/desktop-1.jpg)</br>
[About wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/desktop-2.jpg)</br>
[Music wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/desktop-3.jpg)</br>
[Video wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/desktop-4.jpg)</br>
[Concerts wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/desktop-5.jpg)</br>
[Footer wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/desktop-6.jpg)</br>

#### Mobile
[Home wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/mobile-1.jpg)</br>
[About wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/mobile-2.jpg)</br>
[Music wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/mobile-3.jpg)</br>
[Video wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/mobile-4.jpg)</br>
[Concerts wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/mobile-5.jpg)</br>
[Footer wireframe](https://github.com/krisswiss/Die-Antwoord-Milestone-Project/blob/master/wireframes/mobile-6.jpg)</br>

### Surface

Despite the minimalist approach, I was hoping to reflect the groups image, style and what the Zef culture represent, hence the choice of font, colours and background images. 

## Technologies
1.	HTML
2.	CSS
3.	Bootstrap
4.	JavaScript – to auto close button in NavBar.

### Existing Features:
-	External link to read more about the Zef culture – accessible by clicking on the text under text describing the band.
-	Spotify players allow users to listen to the music clips and also will direct to Spotify platform, where full albums can be explored.
-	YouTube Video let users watch Die Antwoord clip being a great representation of Zef Culture – could be played/opened internally, but also in YouTube.
-	Lyrics buttons under Spotify players and YouTube video let users open pdf file with lyrics to the songs and download it.
-	Info buttons in Concerts section direct users to external website to obtain more information about the concert, venue, tickets, etc.
-	Exclusive updates form – by submitting email address – allow users to sign up to newsletter.
-	Contact form in footer section allow user to contact the admin of the site.
-	Social Links icons are clickable and will bring the user to the social media profiles of the band.

### Features left to implement:
- In the future I would love to be able to add functionality to actually send a message through subscribe and contact forms.
- I would like to also add some text behind YouTube Video (not visible for the user) with related keywords, which would help seo.
- I would like to also add css variables to make the process of changing multiple elements (like colours) easier and more automated (grouped).

## Testing
I believe I have achieved my goals by providing the user with clean, simple and intuitive design, but at the same time representing an abstract Zef Culture image.</br>
Information is easily accessible. Easy to read.  All external links open in new tab, so the user will not forget where they came from.</br>
All links with music and video work well. Lyrics are easily accessible and downloadable in user friendly pdf format.</br>
Every form on the page works and indicates if there is an empty field or incorrect format (email).</br>
Social links icons and tour “info” buttons work as intended. Also added an indication - when hovered over, the text colour and change.</br>
All links have been manually tested to verify they are pointing to the correct destination.</br>
All forms have been manually tested to make sure they will not allow to submit an empty field or incorrect email address. If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload.</br>
Site has been tested for responsiveness with google inspect tool, but also on my own Laptop, tablet and mobile. In addition to this, I have shared my link with several friends, which tested it all on different devices (Sony Z5 compact, Samsung S8, Huawei P20lite), operating systems(windows, mac os) and browsers(chrome, safari, internet explorer) and confirmed they didn’t come across any issues.</br>
HTML and CSS Code has been validated in w3 validator with no major issues.</br>
The only errors that are showing are for HTML code regarding the comments length and iframes attribute being recognized as “obsolete”, but have no effect on site functionality. In fact, I believe, that separating text with such a long comments makes it easier to read.

## Deployment
Website is hosted using GitHub pages, deployed directly from the master branch.</br>
My site is published at [GitHub Sites](https://krisswiss.github.io/Die-Antwoord-Milestone-Project/).</br>
The deployed site updates automatically every time there is new commit added.</br>
To run locally, you can clone this repository directly into the editor of your choice by pasting 'git clone https://github.com/krisswiss/Die-Antwoord-Milestone-Project.git' into your terminal.

## Credit 
The text for About section was copied from [Wikipedia article](https://en.wikipedia.org/wiki/Die_Antwoord)

## Media
The photos for the site were taken from:
[Landing page - Die Antwoord official website](http://www.dieantwoord.com/wallpaper/)</br>
[About section - Pinterest](https://www.pinterest.ie/pin/499618152396393464/)</br>
[About section - Pinterest](https://www.pinterest.ie/pin/362469470004678654/visual-search/?cropSource=6&h=906&w=544&x=10&y=10)</br>
[Music background - Wallpapercave](https://wallpapercave.com/w/U0LuPjL)</br>
[Video background - Christian Backgrounds](http://christianbackgrounds.info/new_images/32/63081921-die-antwoord-wallpapers.jpg)</br>
[Concerts - Weheartit](https://weheartit.com/entry/145256258)</br>

## Acknowledgements
The JavaScript function to auto close the nav button dropdown was taken from [here](https://mdbootstrap.com/support/general/auto-close-navbar-when-click-on-link-responsive-mode/)
provided by  Marta Szymanska.</br>
The footer section code was copied from [Code Institute Resume Mini Project](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/17-adding-contact-form) and changed to my needs.</br>

The inspiration for the choice of the band came from my partner Chakra O’Connor.</br>

***This is for educational use.***
