# The Beach Boys

Mythware is an agile project management web application. Providing features from brainstorming tools i.e. the unicorn-inator, to project planning and completion. In addition, Mythware provides an issues tracker, where users can track and submit new issues to have bugs resolved for free or submit tickets requesting additional features, for a cost.

## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.


## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features

For some/all of your features, you may choose to reference the specific project files that implemented them, although this is entirely optional.

- Feature 1 - allows users X to achieve Y, by having them fill out Z.

- **Feature 1: User Authentication.** The project should include an authentication mechanism, allowing a user to register and log in. There should be a good reason as to why the users would need to log in e.g. a user would have to register to persist their shopping cart between sessions, otherwise it will be lost.
- **Feature 2: Stripe Payments (Django App).** At least one of your Django apps should contain some e-commerce functionaity usins Stripe. This may be a shopping cart checkout, subscription-based payments or single payments etc.
- **Feature 3: User Requests.** Include at least one form with validation that will allow users to create and edit models in the backend, in addition to the authentication mechanism.
- **Feature 4: Responsive UI.** The UI should be responsive, use either media queries or a resonsive framework such as Bootstrap to make sure the site looks well on all commonly-used devices.
- **Feature 5: Free Bugs and Services.** Free services for previously developed applications or answered issues.
- **Feature 6: Paid Bugs and Services.** Develop new applications, resolve bugs on applications, not previously developed by Website Solutions.
- **Feature 7: User Ticket Request.** Ticket on an issues tracker, describing a users request. Allows users to create tickets, comment on tickets and show the status of the ticket, i.e. Open, In Progress, Complete. Issues will come in 2 varities. Free and Paid.
- **Feature 8: Upvoting.** To prioritise work, useers will be able to upvote bugs, signifying 'I have this too'
, and upvote feature requests, signifying 'I want to have this too'. Whilst upvoting is free, to upvote a feature request, users would need to pay some money, with a minimum amount of your choice, to pay for your time working on it. In turn, you promise always to spend at least 50% of your time working on developing the highest-paid feature.
- **Feature 9: Graphs.** To offer transparency to your users, you decide to create a page that contains some grpahs showing how many bugs or features are tended to on a daily, weekly and monthly basis, as well as the highest-voted bugs and features.
- **Feature 10: Contact.** For users to directly contact developers/company.
- **Feature 11: Blog.**
- **Feature 12: Social Links.**
- **Feature 13: Documentation.** To allow new developers that join the company to get up and running as quickly as possible.
- 
- **Feature 15: Video.**
- **Feature 16: Search.**
- **Feature 17: Subscribe to news.**

### Features to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Django]()
    - This project uses **Django** and is composed of multiple apps, an app for each reusable component in the project.
- [Database]()
    - The project will need to connect to a database e.g. sqlite or Postgres, using Django's ORM.
- [JavaScript]()
    - The front end should contain some JavaScript to enhance the user experience.
- [Python/Django packages]()
    - Whenever relevant, the backend should integrate with third-party Python/Django packages, such as Django Rest Frawmwork, etc. Strive to choose the best tool for each purpose.
- [Travis CI]()
    - Make sure to test your project extensively. In particular, make sure that no unhandled exceptions are visible to users, under any circumstance. Use autoamted Django tests wherever possible.
- [Jasmine Tests]()
    - For your JavaScript code, consider using Jasmine tests.

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


**Manual testing**, ongoing via `Cloud 9`, `Run`. Once each functionality code developed, checked operated as expected in the web browser by walking through each functionality. The following bugs were encountered:

1. **Feature x**
    1. **Bug/Expected Output** - . **Issue** - . **Fix** - Scanned code. .


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









### 1960s Rock Band Website
1. Landing Page: Photo of the band.
2. About: Brief description of the band.
3. Videos: Section to showcase videos and download tracks.
4. Music: Section to showcase music and download tracks.
5. Contact: Section for general contact and event bookings. Social links to follow the band.

### Functionalities and Technologies
1. Bootstrap: Nav scrolling bar [template](https://github.com/BlackrockDigital/startbootstrap-scrolling-nav) including responsive web design.
2. Additional Bootstrap: `Font Awesome`link added into `index.html` `<head>` section for social icons.
3. Cloud 9 IDE: Used to build the project end to end.
4. HTML & CSS: Code added to build each section of project.
5. Chrome Dev Tools: Used for ongoing inspection of elements and to perform final UAT.
6. GitHub: Used for version control and backup of project.

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
7. 



Bugs

Boostrap CSS not overrding = Social links CSS, Footer Spacing - spent significant time, many hours ove a number of days, trying to fix this via code as it was not rendering in brower via Run. Figured out that the chrome cache needed to be cleared for CSS updates to apply. And used id / # to overwride as a higher class.
Call to action text not standing out - adjusted photo coloring and uploaded a new photo.
Bootstrap grid not working in videos and audio
Used video tag where should have used audio tag
Videos showing black line/controls nudged above thumbnail - sizing off for grid, updated from 350 to 340.
call out not responsive
Modal text centre aligned, updated <div> tags, throwing out alignment.