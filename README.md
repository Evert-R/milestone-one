# Project's name
## De Ware Boembep
 
## UX

### For who 
- This website was created for the dutch Hip-Hop group "The Chill Oud Posse" and their record label "Dutch Hip-Hop Gems"

### targeted at
- Worldwide hip-hop fans between their thirties and fifties. As some tracks and much of the written content of the release is in dutch the main fanbase will be from Holland. The main language however will be english, wich is common in this subculture. Leiden is the home city of the group so we expect most fans to be from there.

### what does the group want to achieve with this website
- Last year the Chill Oud Posse released a 12" vinyl record to celebrate 30 years of music making, as well as to honour a band member that had recently passed away. It was planned then to release the music for free after some time of selling the record, as this is a non-profit project and the record was released in a limited edition. Its purpose was to be a collectors item as well as an historic documentation of the beginning of Hip Hop in Leiden. This website will hold all the contents of the original release in digital form. The music will be available as a soundcloud stream, as well as individual downloads. All album art will be viewable in a carousel. As an addition the video of the release party, wich was held at Nowas recordstore in Leiden, will be availabe as a youtube stream from the website. 

### What does the record label wish to achieve with this website
- The record label wishes to raise some attention back to the label as the upcoming record (DG003) is about to be released as well as to sell some more records of this release (DG002)

### User stories
- As a user who already bought the record I want to be able to stream or download the music to be able to listen to it everywhere I want. I'll also want to see the video of the releaseparty and be notified of any further projects.
- As a user who missed the record release I would want the same thing as above plus information where to buy the record.
- As a user with no prior knowledge I want all of the above plus links to all the information about the initial project.
- As a recordstore owner or an artist I want to be linked to the record label.

### Mocku-ups
The mock-ups for this project are in the UXD folder wich you will find in the root of this project.

### Concept
- This will be one long scrollable page, with the feel of multiple pages. 
- The first and last page will only show the front and back cover of the record to imitate the real album with the digital content 'inside'. 
- The menu will allways be visible at the top of the screen and will hold icons only. They will allways be the same, both on desktop as on mobile. 
- The menu items will visually scroll the page before you, so you'll quickly be able to see what more there is to discover and also get a glimpse of the album-art wich is used between the sections. 
- Each section will have arrows to scroll up and down as well as an icon to centralize the section on the screen. 
- As an additon the scrolling will snap to the top of the section when you scroll by mouse or when swiping. 
- The website is meant to be as intuitive and practical as possible. The information is mostly in the content provided. 
- Scrolling down further from the back-cover or clicking another arrow will take you down to the credits in the footer.
- The site will be fully responsive and optimized to be viewed on different screen sizes and devices.
 
### Basic features
- Long scrollable page with snapping to the sections
- Sticky top menu, wich makes it 'feel' like multiple pages
- Menu with icons only for an intuitive design with an alternative for visual impaired people
- Icons in the upper right corner of the sections to instantly center them on the screen
- Arrow icons the lower right corner to scroll a section up or down
- mouse hover tooltips for icons and links
- Smooth scrolling when you use the menu, so you see the whole page scroll by
- Static pictures below the sections for a nice scrolling effect
- fully responsive design
- Always visible social media links at the left side on wider screens
- Horizontal bar of social icons for the smaller screens
- Record front cover as first page wich will always be visible behind the other transparent pages
- Info section with a short introduction
- Stream section with an embedded soundcloud playlist
- Download section for the MP3/Flac version of the record
- Cover-art section to showcase the album-art
- Releaseparty section with an embedded youtube video of the releaseparty
- Back cover of the record. 
- Footer with credits and links to contributers to both the website as the record.

### Optional Features
- Option to switch to the dutch language.
- full screen art carousel in new tab

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
- [css-tricks](https://css-tricks.com/NetMag/FluidWidthVideo/Article-FluidWidthVideo.php)
    - Responsive iframe for youtube
- [Online-convert](https://image.online-convert.com/convert-to-ico)
    - Convert jpg image to ico for favicon
- [Photoshop CS6](https://www.adobe.com/products/cs6.html)
    - Image editing 
- [Steinberg Cubase 10](https://new.steinberg.net/cubase/) 
    - Converting music from Wav to Mp3 and FLAC


## Testing

### Known issues
- Background image not showing on google chrome mobile (Android)

### Fixed issues
- Overlay navigation not working on medium width

## Deployment
- The audio files are hosted at [boembep.rotmuziek.nl](https://boembep.rotmuziek.nl)
    - This is my own domain, wich will hold the website once it is completed and aproved.

### Github Pages
- This project was deployed via github pages from the '''master branch'''
    - ```Settings -> GitHub Pages```
    - [https://evert-r.github.io/milestone-one](https://evert-r.github.io/milestone-one)

### Local
- To run this website locally use the following command in your terminal
    - ```clone https://github.com/Evert-R/milestone-one.git```
- To cut ties with this repository
    - ```git remote rm origin```

### Live
- To run this website live, copy all files and folders to the root directory of your webserver.

## Credits

### Content
- [Evert Rot](https://evertrot.nl)
    - Webdesign/coding
    - About-section text.
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
