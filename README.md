# The Beach Boys

This website is a static (front-end only) application for The Beach Boys, 1960's rock band. The primary target audience are current fans, potential fans and customers. Users can sign up for news, read an overview about the band, watch and download videos, listen to and download audio tracks, contact the band, request a booking and follow the band on social media.

## UX

The following section describes the UX process for this project.

#### UX Process
1. **The Beach Boys** - Reviewed The Beach Boys videos, music and website to understand this genre, fans, potential fans and customers.
2. **Layout** - Reviewed Code Institute learnings to date, Bootstrap documentation and online templates to extract design ideas.
3. **User Stories** - Walked through user stories and how the website will achieve these.
    1. **Photo of the band** - As a fan, potential fan or customer, I want to view an up-to-date photo of the band to get a sense of their vibe.
    2. **Subscribe to News** - As a fan, potential fan or customer, I want to subscribe to The Beach Boys news, to receive updates on the bands members, their concerts and new music.
    3. **About** - As a fan, potential fan or customer, I want to read a summary about The Beach Boys, to understand their background to date.
    4. **Videos** - As a fan, potential fan or customer, I want to watch some of The Beach Boys videos, for entertainment, to download videos and to see their performances should I choose to book them for an event or want to book a live concert.
    5. **Audio** - As a fan, potential fan or customer, I want to listen to some of The Beach Boys audio tracks, for entertaiment, to download audio tracks and to listen to their music should I choose to book them for an event or want to book a live concert.
    6. **Contact** - As a fan, potential fan or customer I want to be able to contact the band, to submit feedback or request to book the band for an event.
    7. **Social Media Icons** - As a fan, potential fan or customer I want to be able to follow the band on social media, to be a part of their journey and interact with them online.
4. **Wireframe** - Sketched the wireframe on paper, to include a section for each user story, delivering a clear design to connect the bands needs to the users needs.

## Features
 
### Existing Features

The following section describes all the front-end features in this project.

1. **The Beach Boys** - Landing page navbar menu item. When selected brings users to view a photo of the band, view a call to action header. It allows provides users to select a button to sign up to news, by having them fill out the modal that appears once the user selects 'Sign Up!'
2. **About** - About navbar menu item. When seleted brings users to view the about section, which contains a summary about The Beach Boys, to understand their background to date.
3. **Videos** - Video navbar item. When selected brings users to view the video section which showcases videos, for entertainment, to download videos and to see their performances should I choose to book them for an event or go to see them perform live.
4. **Audio** - Audio navbar item. When selected brings users to listen to auio tracks of the band which showcases audio tracks, for entertaiment, to download and to listen to their music should I choose to book them for an event or go to see them perform live.
5. **Contact** - Contact navbar item. When seleted brings the users to the contact section, to be able to contact the band, to submit feedback or to book the band for an event.
6. **Social Media Icons** - Icons for Facebook, Twitter and Youtube, when selected brings users to each social media page. Allows users to be a part of the bands journey and interat with them.

### Features to Implement
1. **Merchendaise**
2. **Book live concerts**
3. **Live concert schedule**
3. **Videos** - Upgrade to video slider functionality for more streamlined presentation or figure out other ways to enahnce UX/UI.
4. **Audio Tracks** - Upgrade to include thumbnail type photo for each track or figure out other ways to enhance UX/UI.

## Technologies Used

The following section describes all technologies and tools used to construct this project.

- [Cloud 9 IDE](https://aws.amazon.com/cloud9/)
    - The project used **Cloud 9**, online integrated development environment, to construct the code end to end.
- [Bootstrap Template](https://github.com/BlackrockDigital/startbootstrap-scrolling-nav)
    - This project uses **Bootstrap Nav scrolling bar template**, a blank template with main navigation and a grid layout. This blank template was used as a starting block and tailored/bult upon for this specific website. Index.html and Main.CSS predominatly all developers code. All other code included with Bootstrap template.
- [Font Awesome](https://fontawesome.com/)
    - This project uses **Font Awesome**, a library of icons, to add the social media icons in the footer.
- [HTML](https://en.wikipedia.org/wiki/HTML)
    - This project uses **HTML**, the standard markup language, to build the layout for the index.html page. HTML code specific to this project was added in the index.html file.
- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - This project uses **CSS**, a style sheet language, to add styling to the index.html page. The **main.css** file was added to the Bootstrap template to add custom styling.
- [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools/)
    - This project uses **Chrome Dev Tools**, a set of web developer tools, to continously test and inspect that the web pages are rendering correnctly in the browser.
- [GitHub](https://github.com/)
    - This project uses **GitHub**, a web hosting service, for version control and final project deployment.

> **All other technologies** within this project were included with the Bootstrap template.


## Testing

The following is an overview of testing to ensure all functionality works as intended in this project.

1. **Landing section and Subscribe to News**:
    1. Select the 'Contact' menu on the navbar, and verify that the user is moved to the contact section and away from the landing page.
    2. Select 'The Beach Boys' menu on the navbar, and verify that the user is moved to the landing page.
    3. Select the 'Sign Up' button, and verify that a modal appears.
    4. Complete all user details within the modal, and verify that all fields accept relevant text.
    5. Select 'Sign Up' to submit the users details, and verify that the modal closes.
    
        - **Bug 1** - Càll to action text not standing out for clean reading.
            - **Issue** - Background photo too bright and text size too small.
            - **Fix** - Adjusted photo coloring by reducing brightness and uploaded new photo. Increased text size via custom CSS, i.e. main.css file.
        
        - **Bug 2** - Modal input field text alignemnt skewed.
            - **Issue** - Additional div tags throwing out alignment.
            - **Fix** - Updated div tags to ensure aligment correct.

2. **About Section**:
    1. Select the 'About' menu on the navbar, and verify that the user is moved to the about section.
    2. Select the hyperlink, 'To request a booking, please go to the contact section.', and verify that the user is moved to the contact section.

3. **Videos Section**:
    1. Select the 'Videos' menu on the navbar, and verify that the user is moved to the videos section.
    2. Select play, pause, time slider, volume icon and slider, full screen and download on each video. Verify that all functionalities work as intended.

        - **Bug 1** - Custom CSS i.e. main.css code, not overriding Bootstrap CSS.
            - **Issue** - Website not rendering in browser until cache cleared.
            - **Fix** - Spent significant time, hours over a number of days researching this. Decided to try to clear the cache in chrome and this fixed the issue. Also used id classes in some areas of the custom CSS to override Bootstrap CSS.

        - **Bug 2** - Bootstrap template grid not suitable for video layout.
            - **Issue** - Bootstrap tempalte grid suitable for one column of data.
            - **Fix** - Updated html <div> tags around videos to a bootstrap grid class of 'col-sm-6', to layout two videos side by side on each div row.     
        
        - **Bug 3** - Video controls nudged up on top of thumbnail.
            - **Issue** - Video sizing not fitting into Bootstrap grid layout.
            - **Fix** - Updated video widths from 350 to 340.   
        

4. **Audio Section**:
    1. Select the 'Audio' menu on the navbar, and verify that the user is moved to the audio section.
    2. Select play, pause, time slider, volume icon and slider, and download on each audio track. Verify that all functionalities work as intended.
    
        - **Bug** - Bootstrap template grid not suitable for audio layout.
            - **Issue** - Bootstrap tempalte grid suitable for one column of data.
            - **Fix** - Updated html div tags around videos to a bootstrap grid class of 'col-sm-6', to layout two audio tracks side by side on each div row.
        
        - **Bug** - Each audio track inclues a video thumbnail above the controls.
            - **Issue** - Used a html video tag, but should be a audio tag.
            - **Fix** - Updated all video tags, that should be audio tags.

5. **Contact Section**:
    1. Select the 'Contact' menu on the navbar, and verify that the user is moved to the contact section.
    2. Complete all user details within the form, and verify that all input fields accet the text as intended.

6. **Social Media Icons**:
    1. Scroll to the footer section.
    2. Select the Facebook, Twitter and YouTube icons, and verify that all icon hoover styling is as intended. Verify that all icons open each social media page, in a new browser window.

7. **Responsive Testing**:
    1. In Chrome, right click on the site and select 'inspect', to open the Chrome Dev tools.
    2. Select the toggle device icon, to open the responsive testing windown.
    3. Test how the website is rendering on each device size from Galaxy S5 to iPad Pro.
    
        - **Bug** - Website not fitting into all devices.
            - **Issue** - OPEN BUG.
            - **Fix** - OPEN BUG.

## Deployment
The followng section describes the process to deploy this project GitHub Pages.

1. Create new repository within GitHub.
2. Within GitHub, under <> Code heading, copy 'git remote add origin...' command, paste into IDE terminal and execute.
3. Within GitHub, under <> Code heading, copy 'git push -u origin master' command, paste into IDE terminal and execute.
4. The project now pushed to GitHub.
5. Within GitHub, under Settings heading, go to 'GitHub Pages' section.
6. Select Master branch and save.
7. The project is now published to GitHub Pages and can be viewed in the browser.
8. GitHub Pages URL: [The Beach Boys](https://githhayden.github.io/The-Beach-Boys/).

> **Note:** During the project re-pushed to a new GitHub repo  and lost staged commits up to that point.

## Credits

### Content
- The text for the About section was copied from [Wikipedia](https://en.wikipedia.org/wiki/The_Beach_Boys).

### Media
- The photos used in this site was copied from [WWMT.com](https://wwmt.com/news/local/the-beach-boys-to-headline-tulip-time-2018-tickets-on-sale-nov-9).
- The videos and audio tracks in this site were copied from [YouTube](https://www.youtube.com/) and converted to MP4 and MP3 files.

### Acknowledgements

- I received inspiration for this project from The Beach Boys videos, music and website, from Bootstrap template designs and from Code Institue education.