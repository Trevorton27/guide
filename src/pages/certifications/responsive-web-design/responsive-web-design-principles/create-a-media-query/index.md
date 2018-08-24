---
title: Create a Media Query
---
## Create a Media Query

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/responsive-web-design/responsive-web-design-principles/create-a-media-query/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

I got stuck on this problem, too. Freecodecamp's example syntax for this particular problem is a little bit lacking. Here is a clearer sample based on the syntax of the correct answer:
@media (display parameters/screen size etc) {element to be affected p/img/header etc {CSS rules} }

Notice that the element to be affected ( p/ img / header etc) has its OWN SET OF BRACKETS. Not adding these brackets will invalidate your code and you will fail if you run the tests on freecodecamp.org

Example:
if you want to create a media query where the font size for a paragrapch changes to 8px for a screen height equal to or less than 400 px the correct code would look like this:

 @media (max-height: 400px) {p {font-size: 8px;} }
 
 I hope that's helpful. :-)
