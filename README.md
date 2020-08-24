# Second assignment
- Please use live-server while working on the project
### Scss
- Put all the CSS of the site into a SCSS file
- Use SCSS nesting instead of children selectors
### Images
- For images only the width should be set not the height, so they maintain their original aspect ratio
### Responsivity
- Please make sure that the changes you make going forward don't affect the mobile version negatively.
- Use bootstraps breakpoint for medium screen sizes from the [Bootstrap documentation](https://getbootstrap.com/docs/4.3/layout/overview/#responsive-breakpoints)
  #### In that media query add:
  - Hover effects for all links
  - The links of the main navigation should be displayed next to each other on medium size screens
  - The navigation links should appear in uppercase
  - Set a maximum width for the main container so the content is preventet from running too wide on big screens
### Code quality
- Don't use hr tags. Lines have to be created using border
- Don't use br tags to allign Elements vertically or to create margins. You can use ```display: block``` for vertical alignment and ```margin``` or ```padding``` for margins for example.
### Bonus
- Add styling to the header of the page so that it takes up the entire height of the viewport. Hint: you can use ```vh``` for that. To avoid problems with small screens define the CSS for this in a media query that will only apply it on bigger screens.
