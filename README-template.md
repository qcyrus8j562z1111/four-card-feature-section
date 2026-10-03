## Overview
 
The Four Card Feature Section challenge is a responsive layout project focused on organizing multiple feature cards across different screen sizes.
 
I built the project using a mobile-first approach. On smaller screens, the cards are displayed in a single column. On larger screens, CSS Grid reorganizes the four cards into the desktop layout while keeping the content centered and responsive.
 
My goal was not only to match the supplied designs as closely as possible, but also to practice writing reusable CSS, working with responsive layouts, and using browser DevTools to debug and refine the design.
 
### The challenge
 
Users should be able to:
 
- View the optimal layout for the feature section depending on their device's screen size
- View a single-column card layout on smaller screens
- View the multi-column feature layout on larger screens
 
### Screenshot
 
![Screenshot of my Four Card Feature Section solution](./screenshot.jpg)
 
### Links
 
- Repository URL: [GitHub repository](https://github.com/qcyrus8j562z1111/four-card-feature-section)
- Solution URL: Add Frontend Mentor solution URL after submission
- Live Site URL: Add live site URL after deployment
 
## My process
 
I started by reviewing the supplied mobile and desktop designs, style guide, and starter HTML before writing any styles.
 
I first structured the content with semantic HTML. Each feature was built as a reusable card using a shared `card` class along with a modifier class for the card's individual accent color.
 
For the CSS, I created custom properties for the supplied color palette and added a small reset and the base typography before working on the layout.
 
I built the mobile layout first, using a single-column CSS Grid for the cards. Once the mobile version was working, I added a responsive breakpoint and transformed the same grid into the three-column desktop arrangement.
 
Instead of changing the HTML for desktop, I positioned the existing cards using CSS Grid rows and columns. The Supervisor and Calculator cards span the two-row grid area and are vertically centered, while Team Builder and Karma occupy the two center positions.
 
Throughout development, I regularly compared the implementation with the supplied reference images at different viewport sizes. I also used browser DevTools to inspect applied styles and debug issues instead of adjusting CSS values at random.
 
Git and GitHub were used throughout development with separate commits for meaningful stages of the project.
 
### Built with
 
- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Responsive media queries
- Google Fonts
- Git and GitHub for version control