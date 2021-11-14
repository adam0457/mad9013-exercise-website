# Professor Feedback

## Week 2B ----------------------

Overall, great start! A few small changes:

- Make sure you are properly indenting your code. It makes it difficult to read and understand when the code is poorly indented. The Indent Rainbow plugin will flag improper indentation red to help you
  - It looks like you have your Tab Size in VS Code set to 8, which is very large. I would set it to either 2 or 4 at max
- the `<h1>` should be wrapped around the `<img>` inside the `<header>`
- You should avoid typing in all caps on the web, it is bad for accessibility. Right in normal sentence case and then we can style it later with CSS to make it all caps.
- the "Design your brand..." heading should be an `<h2>`
- The logos in the header/footer should be wrapped in an `<a>` linking to the home page

## Week 3 ----------------------

Great work! Here are a few tips to help simplify things up and improve consistency:

- You can simplify your button styles. You've created two separate classes and have duplicated a number lines of code. To simplify, create on `.btn` class that creates the basic button styles and then create a second `.btn-white` that changes to colour to white. This will help keep things consistent as well.
- The same concept can be applied to the banners as a whole. create a basic `.banner` class that applies basic styles like alignment, color, etc. Then use a secondary class to apply overrides for padding and image.

## Week 4 ----------------------

Code Quality: 2.75/3
Design: .75/1
File Organization & Commits: 1/1
Total: 4.5/5

- You should be using the colors provided in the exercise assets repo
- Make sure to review your CSS to insure it is neat and organized, including:
  - remove empty lines inside of CSS rules
  - there should be a space between the selector and the opening curly bracket `{`
  - there should be a space between each ruleset
  - double check indentation 

## Week 5 ----------------------

Code Quality: 2/3
Design: 1/1
File Organization & Commits: 1/1
Total: 4/5

- Use `float: right;` on the footer button to more easily align to the right
- use a combo of `width: 100%` and `max-width: 15rem`; on your logo in the header and footer to create a nice consistent logo size. Using just a percent in the footer is causing it to shrink too small.

## Week 6 ----------------------

Code Quality: 2.5/3
Design: .5/1
File Organization & Commits: 1/1
Total: 4/5

- Add `align-items: center;` to align the logos vertically.
- Add some padding around the logo bar to space it out from the content above and below
- Consider using the `flex` properties to align the content in the header and footer. You've used a few different margins and paddings on the left of logo and the right of the nav which are miss-aligning things.
- Use a more descriptive name for your `.medium` class. It is acting as a modifier of your `.container` to add `flex`, so a classname of `.container-flex` would be more appropriate.
  - You could also reuse that in place of the `.medfooter` which you are repeating code in.
- Sub footer with legal terms is not aligning properly.

## Week 7 ----------------------

Code Quality: 2.75/3
Design: 1/1
File Organization & Commits: 1/1
Total: 4.75/5

- You should name your new file `platform-tour.html` to be consistent with the page `<title>` and link labels
- Try and be more descriptive with your class names! Avoid just numbering off your elements.

## Week 9 ----------------------

Code Quality: 2.5/3
Design: .75/1
File Organization & Commits: 1/1
Total: 4.25/5


- You can only have one `h1` per page, you have two. The "Affordable Pricing for All" heading should be the `h1`
- The Premium column should be highlighted with a different text, button, and background color!
- You do not have the `Ubuntu` Google font linked in your HTML or CSS causing the font to not load properly.

## Week 10 ----------------------

Code Quality: 2.75/3
Design: 1/1
File Organization & Commits: 1/1
Total: 4.75/5

- All `input` need a `label` with text content in it. This is important for accessibility. To visually hide the labels, use the `screen-reader-text` styles discussed in class.
- I would suggest putting the background image on the `section`, not the `main`. That way if there ends up being more content added to the page, you wouldn't need to re-do work.