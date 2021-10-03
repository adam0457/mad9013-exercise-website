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