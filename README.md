# De Ware Boembep

### Deployed version 
[https://evert-r.github.io/milestone-one](https://evert-r.github.io/milestone-one)

## UX

### For who this website is created 
This website was created for the dutch Hip-Hop group 'The Chill Oud Posse' and their record label 'Dutch Hip-Hop Gems".

### At who this website is targeted
This website is targeted at worldwide Hip-Hop fans between their thirties and fifties. We expect most fans to be from Leiden, in the Netherlands, as this is the home city of the group. 

### Wich language is used and why
Though some tracks, and much of the written content of the release is in dutch, the main language for the website will be in english. This is common in this subculture. Offcourse this will also target more people. 

### What does the group want to achieve with this website
Last year the Chill Oud Posse released a 12" vinyl record to celebrate 30 years of music making, as well as to honour a band member that had recently passed away. As this was a non-profit project, and the record was released in a limited edition, it was planned from the start to release the music for free after some time of selling the record. Because this collectors item was also ment as an historic documentation of the beginning of the Hip-Hop scene in Leiden, this website will hold all the music, artwork and articles of the original release in digital form, so it will be available for everyone.

### What does the record label wish to achieve with this website
The record label wishes to raise some attention back to the label as the upcoming record (DG003) is about to be released as well as to sell some more records of this release (DG002).

### User stories
1. As a user who already bought the record I want to be able to stream or download the music and listen to it everywhere I want. I'll also want to see the video of the releaseparty and be notified of any future projects.
2. As a user who missed the record release I would want the same thing as above plus information about where to buy the original record.
3. As a user with no prior knowledge I want all of the above plus links to all the information about the initial project.
4. As a recordstore owner or an artist I would want to be linked back to the record label.
5. As a historian I would want to read all the articles that were included in the release.

### Mock-ups
The mock-ups for this project are in the UXD folder wich you will find in the root of this project.
- [Wireframe1](UXD/wareboembep-mockup-1.jpg)
- [Wireframe2](UXD/wareboembep-mockup-2.jpg)

### Concept
This will be one long scrollable page, but with the feel of multiple pages. The first and last page will show the front and back cover of the vinyl release with all the original content in digital form in between. Thus simulating the record in its cover.

The menu will always be visible at the top of the screen and will show icons only. They will allways be the same, both on desktop as on mobile. The website is meant to be as intuitive and practical as possible. The information is mostly in the content provided.

The menu will visually scroll the page before you when you select an item, so you'll quickly be able to see what more there is to discover and also get a glimpse of the album-art wich is used as a visual effect between the sections.

Each section will have arrows to scroll up or down as well as an icon to centralize the section on the screen. Also the scrolling will snap to the top of a section when you scroll by mouse or when swiping. This is to benefit the 'feel of multiple pages'.

On bigger screens there will be social media links on the left, wich will always be visible. On the smaller devices they will appear on the bottom of each section.

The site will be fully responsive and optimized to be viewed on different screen sizes and devices.

Scrolling down from the back-cover will bring you to the credits in the footer. Here you will also find a form to sign up for future updates.
 
### Basic features
- Long scrollable page with snapping to the sections.
- Sticky top menu, wich makes it 'feel' like multiple pages.
- Menu with icons only for an intuitive design with an alternative for visual impaired people.
- Icons in the upper right corner of the sections to instantly align them vertically on the screen.
- Arrow icons in the lower right corner to scroll a section up or down.
- Mouse-hover tooltips for icons and links.
- Smooth scrolling for menu items.
- Static pictures below the sections for a nice scrolling effect.
- Fully responsive design.
- Always visible social media links at the left side on wider screens.
- Horizontal bar of social icons for the smaller screens.
- Record front cover as first page wich will always be visible behind the other transparent pages.
- Info section with a short introduction.
- Stream section with an embedded soundcloud playlist.
- Download section for the MP3/Flac version of the record with help info on zip-files.
- Cover-art section to showcase the album-art.
- Releaseparty section with an embedded youtube video of the releaseparty.
- Back cover of the record.
- Footer with credits and links to contributers to both the website as the record.
- Form to sign up for future updates by mail.
    - In this release the form will do nothing but reload the page, as its functionality is out of the scope of this project.

### Optional Features to be implemented later
- Option to switch to the dutch language.
- Full screen art carousel in new tab
- Functional form wich sends an email to the record company

## Technologies Used
- [VSCode](https://code.visualstudio.com)
    - Code Editor
- [Xampp](https://www.apachefriends.org)
    - Local deploymemt
- [Git bash](https://gitforwindows.org)
    - Version control from windows
- [Font-Awesome](https://fontawesome.com)
    - Icons
- [Bootstrap](https://getbootstrap.com)
    - Responsive grid / Navigation bar / Image carousel
- [Google Fonts](https://fonts.google.com)
    - Fonts (Source code pro/Allerta Stencil)
- [css-tricks](https://css-tricks.com/NetMag/FluidWidthVideo/Article-FluidWidthVideo.php)
    - Responsive iframe for youtube
- [Autoprefixer](https://autoprefixer.github.io)
    - CSS prefixes for different browsers 
- [Online-convert](https://image.online-convert.com/convert-to-ico)
    - Convert jpg image to ico for favicon
- [Photoshop CS6](https://www.adobe.com/products/cs6.html)
    - Image editing 
- [Steinberg Cubase 10](https://new.steinberg.net/cubase/) 
    - Converting music from Wav to Mp3 and FLAC


## Testing
### Tools
- [w3c Markup Validation](https://validator.w3.org)
    - HTML validation: No errors
- [w3c CSS Validation](https://jigsaw.w3.org/css-validator/validator)
    - CSS validation: No errors

### Users
1. As a user who already bought the record I clicked on the download button on the front page and went straight to the download section. Meanwhile I see the page scroll by so after I downloaded the music I go back to discover the rest while listening to the music from the stream section.
2. As a user who missed the record release I selected the musical note on the menu to go straight to the stream section. From there I click on the shopping cart wich leads me to the website where I can buy the record.
3. As a user with no prior knowledge I scrolled down manually to read the about section. Scrolled further to listen to the music, then dowload the music, watch the artwork, view the releaseparty video, and finally end up at the credits following links to all the contributors of this project.
4. As a recordstore owner or an artist I click on the logo of the record company to go to its website.
5. As a historian I clicked on the eye in the menu to go directly to the articles and artworks in the carousel.

### Responsive behaviour


### Known issues
- Fixed background image not showing on google chrome mobile (Android)
    - Fixed backgrounds are disabled for this browser. I fixed this by putting a second background image on top of the fixed one, wich will scroll away as you proceed. It kinda takes away the original effect, but otherwise chrome mobile would show a blank front page. As this is a very common browser this would be unacceptable. In the future I will fix this so the extra background will only be visible on chrome mobile, but for now it's out of the scope for this project as it will require php or javascript.

### Fixed issues
- Menu is not centered
    - Used translateX to make up for the letter spacing
- Overlay navigation not working on medium width

## Deployment
### Github Pages
This project was deployed via github pages from the ```master branch```

#### This was done following this procedure:
1. Goto the repository on Github: [Github](https://github.com/Evert-R/milestone-one)
2. Goto ```Settings```
3. Select ```Github pages```
4. Use the ```select source``` dropdown to select the ```master branch```
5. Click ```Save```

The Github pages are now being built.

[Click here to view the deployed website](https://evert-r.github.io/milestone-one)

> The audio files are hosted at: 
> [boembep.rotmuziek.nl](https://boembep.rotmuziek.nl)
> This is my own domain, wich will also host the website once it is completed and aproved.

### Local
To clone this website locally use the following command in your terminal:
- ```git clone https://github.com/Evert-R/milestone-one.git```

To cut ties with this repository:
- ```git remote rm origin```

### Live
- To run this website live, copy all files and folders to the root directory of your webserver.

## Credits

### Content
- [Evert Rot](https://evertrot.nl)
    - Webdesign/coding
    - Text in the about section
### Media
- [Pop-Eye/Colourcastle](https://www.colourcastle.nl)
    - Background-image/ Front album cover
- [Remko Koopman](https://remkokoopman.nl) 
    - Album cover/inlay design
- [Marieke Mamarazzi](https://www.mmmriek.com) 
    - Pictures in streaming, download and releaseparty sections
- [Chill Oud Posse](https://rotmuziek.nl)
    - Music
- [Evert Rot](https://evertrot.nl)
    - Releaseparty video

### Acknowledgements
