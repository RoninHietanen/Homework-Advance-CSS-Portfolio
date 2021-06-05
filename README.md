# Homework-Advance-CSS-Portfolio - My Portfolio
This is the README of my portfolio homework for my bootcamp course.

Below is the link to the live page:

https://roninhietanen.github.io/Homework-Advance-CSS-Portfolio/

# General Information:

This page contains 4 image links, contact information, about me, and resume.

## This page was created using:
- Visual Studio Code - HTML and CSS
- GitHub Pages

## This page's HTML contains:

- 4 working page jump/scroll links in the navigation bar:
  - "About Me"
  - "My Work"
  - "Contact Me"
  - "Resume"
- 6 headers:
  - 2 in the header.
  - 4 in different sections that the nav links scroll to.
- An "About Me" section with plain text.
- 4 image links in the "My Work" section:
  - 1 going to a live webpage with image preview of the page.
  - 3 going to a youtube video of calming music and image of "coming soon".
- A "Contact Me" section with phone and email links.
- A "Resume" section with a pdf resume link.

## This page's CSS contains:
- A fixed header.
- A continuious font family and background colour.

`body {
  background-color: #ddcdcd;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}`

- 6 colours overall:
  - page colour - #ddcdcd
  - header colour - #7c2a78
  - the line colour - rgb(156, 0, 0)
  - shadow colour - #aaaaaa
  - border colour - rgba(0, 0, 0, 0.507)
  - header font colour - #230131.
- 16 class selectors:
  - .header
  - .header h1
  - .header h2
  - .header nav
  - .header nav ul li
  - .aboutme h3
  - .mywork h4
  - .mywork article
  - .mywork article
  - .my
  - .work a img
  - .work2 a img
  - .work a:hover img
  - .work2 a:hover img
  - .contactme h5
  - .contactme ul li
  - .Resume h6
- 1 universal selector:
  - *
- 3 element/type selectors:
  - html
  - body
  - p
- 5 media queries on (max-width: 676px):
  - .header, body
  - p
  - .contactme ul li
  - .mywork article
  - h3, h4, h5, h6
