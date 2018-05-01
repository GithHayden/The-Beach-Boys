### Purpose

* Landing Page: Photo of the band.
* About: Brief description of the band.
* Videos: Section to showcase videos and download tracks.
* Music: Section to showcase music and download tracks.
* Contact: Section for general contact and event bookings. Social links to follow the band.

### Functionalities and Technologies

* Bootstrap: Nav scrolling bar [template](https://github.com/BlackrockDigital/startbootstrap-scrolling-nav) including responsive web design.
* Additional Bootstrap: `Font Awesome`link added into `index.html` `<head>` section for social icons.
* Cloud 9 IDE: Used to build the project end to end.
* HTML & CSS: Code added to build each section of project.
* Chrome Dev Tools: Used for ongoing inspection of elements and to perform final UAT.
* GitHub: Used for version control and backup of project.

### Deployment

1. Bootstrap Template: Saved into `Cloud 9 IDE` workspace.
2. Cloud 9 IDE: Updated in line with wireframe for this project. Assets folder created, and files saved into the folder. Additional list item added to navbar. List items renamed to align with this project.
3. Each nav section updated with relevant HTML and styled with Bootstrap classes or CSS on `main.css`. Social Links CSS styling included within `index.html` `<style>`tag to override Bootstrap template.
4. UAT: Final web design inspected via `Cloud 9 IDE`, `Run`. Responsive web design tested via `Chrome Dev Tools`, `Toggle Device Toolbar`.
5. Staged Project Backup: Pushed to `GitHub` repo via `Linux` terminal in incremental stages.
```
NOTE: At end of project, re-pushed to a new GitHub repo to update project naming conventions,
thus, lost all staged commits.
```
6. Final Project Backup: Pushed to `GitHub` repo via `Linux` terminal.
7. Deployed via GitHub Pages: https://githhayden.github.io/The-Beach-Boys/

### Developer 'To Do' Notes

* Current iteration = i2.
* Subsequent iterations:
    1. Videos - add additional videos.
    2. Music - rename to Audio and add additional tracks.
    3. Convert 'For bookings please go the contact section' into a hyperlink.
    4. Add a "call to action" button or any other text around the bottom of the page, to help the user understand what they should do next.
    5. Move social buttons inside footer.
    6. Readme - add short description of the project in general, before diving into the specific sections. Explain who the target audience and what the site aims to provide them with.
    7. Gulp file - describe in the readme's deployment section and explaining how it works.
    8. CSS (Seperation of Concerns) - Move inside .css file rather than inside HTML.
    9. HTML - remove p tags as not required.
    10. Across all of the code files, particularly in the css, add more comments explaining the purpose of each section and the overall structure.
    11. Ampersand (&) is a special character in HTML used to add special entities to the text, whenever want to include it as is, use the sequence "&amp;".
    12. Testing - add testing section to readme.
        a) Describe the process by which you made sure that the functionality all works as intended. 
        b) Structure around the list of scenarios - e.g. I clicked on the Videos link in the navbar, then clicked play to verify that the video plays correctly and clicked download to verify that I could download it to my computer.
        c) Describe any interesting bugs and how you addressed them, and whether there were any issues that you didn't/couldn't fix.
    13. Be specific about the template used - what I took from it and what code I wrote. Provide full credit. Check for copyright notices on top of the css and all files and add.