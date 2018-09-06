# The Beach Boys

This website is a front-end application for The Beach Boys, 1960's rock band. The primary target audience are current fans, potential fans and customers. Users can sign up for news, read an overview on the band, watch videos, listen to audio tracks, download audio tracks, contact the band to request a booking and follow the band on social media.

## UX
 
The following is an overview of the UX process for this project.

#### UX Process
1. **The Beach Boys** - Reviewed The Beach Boys videos, music and website to understand this genre, fans, potential fans and customers.
2. **Layout** - Reviewed the Code Institute learnings, Bootstrap documentation and online templates to extract design ideas.
3. **User Stories** - Understood user requirements and how the website will achieve this.
    1. **Subscribe to News** - As a fan, potential fan or customer, I want to subscribe to The Beach Boys news, to receive updates on the bands members, their concerts and new music.
    2. **About** - As a fan, potential fan or customer, I want to read a summary about The Beach Boys, to understand their background to date.
    3. **Videos** - As a fan, potential fan or customer, I want to watch some of The Beach Boys videos, for entertainment, to download videos and to see their performances should I choose to book them for an event or go to see them perform live.
    4. **Audio** - As a fan, potential fan or customer, I want to listen to some of The Beach Boys audio tracks, for entertaiment, to download audio tracks and to listen to their music should I choose to book them for an event or go to see them perform live.
    5. **Contact** - As a fan, potential fan or customer I want to be able to contact the band, to submit feedback or to book the band for an event.
    6. **Social Media Icons** - As a fan, potential fan or customer I want to be able to follow the band on social media, to be a part of their journey and interact with them.
4. **Wireframe** - Sketched the wireframe on paper, to include a section for each user story, delivering a clear design to connect the bands needs to the users needs.

## Features

The following is an overview of each feature within this project.
 
### Existing Features

For some/all of your features, you may choose to reference the specific project files that implemented them, although this is entirely optional.

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
    - This project uses **Bootstrap Nav scrolling bar template**, a blank template with main navigation and a grid layout. This blank template was used as a starting block and tailored for this specific website.
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
    
        1. **Bug** - Càll to action text not standing out for clean reading.
        2. **Issue** - Background photo too bright and text size too small.
        3. **Fix** - Adjusted photo coloring by reducing brightness and uploaded new photo. INcreased text size via custom CSS, i.e. main.css file.
        
        1. **Bug** - Modal input field text alignemnt skewed.
        2. **Issue** - Additional <div> tags throwing out alignment.
        3. **Fix** - Updated <div> tags to ensure aligment correct.

2. **About Section**:
    1. Select the 'About' menu on the navbar, and verify that the user is moved to the about section.
    2. Select the hyperlink, 'To request a booking, please go to the contact section.', and verify that the user is moved to the contact section.

3. **Videos Section**:
    1. Select the 'Videos' menu on the navbar, and verify that the user is moved to the videos section.
    2. Select play, pause, time slider, volume icon and slider, full screen and download on each video. Verify that all functionalities work as intended.

        1. **Bug** - Custom CSS i.e. main.css code, not overriding Bootstrap CSS.
        2. **Issue** - Website not rendering in browser until cache cleared.
        3. **Fix** - Spent significant time, hours over a number of days researching this. Decided to try to clear the cache in chrome and this fixed the issue. Also used id classes in some areas of the custom CSS to override Bootstrap CSS.

        1. **Bug** - Bootstrap template grid not suitable for video layout.
        2. **Issue** - Bootstrap tempalte grid suitable for one column of data.
        3. **Fix** - Updated html <div> tags around videos to a bootstrap grid class of 'col-sm-6', to layout two videos side by side on each div row.     
        
        1. **Bug** - Video controls nudged up on top of thumbnail.
        2. **Issue** - Video sizing not fitting into Bootstrap grid layout.
        3. **Fix** - Updated video widths from 350 to 340.   
        

4. **Audio Section**:
    1. Select the 'Audio' menu on the navbar, and verify that the user is moved to the audio section.
    2. Select play, pause, time slider, volume icon and slider, and download on each audio track. Verify that all functionalities work as intended.
    
        1. **Bug** - Bootstrap template grid not suitable for audio layout.
        2. **Issue** - Bootstrap tempalte grid suitable for one column of data.
        3. **Fix** - Updated html <div> tags around videos to a bootstrap grid class of 'col-sm-6', to layout two audio tracks side by side on each div row.
        
        1. **Bug** - Each audio track inclues a video thumbnail above the controls.
        2. **Issue** - Used a html <video> tag, but should be a <audio> tag.
        3. **Fix** - Updated all <video> tags, that should be <audio> tags.

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
    
        1. **Bug** - Càll to action text not responsive on smaller devices.
        2. **Issue** - 
        3. **Fix** - 


## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X

### Development Process and Deployment
1. Bootstrap Template: Saved into `Cloud 9 IDE` workspace.
2. Cloud 9 IDE: Updated in line with wireframe for this project. Assets folder created, and files saved into the folder. Additional list item added to navbar. List items renamed to align with this project.
3. Each nav section updated with relevant HTML and styled with Bootstrap classes or CSS on `main.css`. Social Links CSS styling included within `index.html` `<style>`tag to override Bootstrap template.
4. UAT: Final web design inspected via `Cloud 9 IDE`, `Run`. Responsive web design tested via `Chrome Dev Tools`, `Toggle Device Toolbar`.
5. Git and GitHub: Used for version control and to deploy backup up project.
```
NOTE: At end of project and as part of the learning curve, re-pushed to a new GitHub repo to update project naming conventions,
thus, lost all staged commits.
```
6. Deployed via GitHub Pages: [1960s Rock Band Website](https://githhayden.github.io/The-Beach-Boys/).



Be specific about the Bootstrap template used - what I use from it & what code I wrote. Figure out how to maintain clear seperation.
Povide full credit in commentary/on files and in README.
Check for copyright notices on top of the CSS/allfiles and include.
End to End build - check all code/commentary clean, test all features, test responsive, ensure streamlined.
Spellcheck.
Push final version to GitHub.

