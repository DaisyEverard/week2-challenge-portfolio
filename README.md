# week2-challenge-portfolio

## Link to deployed site

## Preview

<p align="center">
  <img src="" width="350" alt="screenshot of site">
</p>

## Description

A Portfolio Page to showcase deployed projects I have worked on to potential employers. 

Contains:
- Header and Hero Sections
- Recent profile photo
- 'About Me' section
- Links to work. 2 functional, 2 placeholder in CSS grid.
- Contacts section

## Issues and Solutions

1. Positioning Profile Picture

Put img in a div, not necessary in this instance but could be important with different setup.
Used fixed absolute units for the height and width of the image then used media queries to make image size suitable for different displays. 

2. Centrally positioning contacts

The divs should be flex columns containing content for each type of info (here #contact-label and #contact-info), not for the linked pairs of info. 
- Overall section was flex row
- subtitle width 100%
- flex columns with align-items set seperately at end and start

## Initial Wireframe

<p align="center">
  <img src="challenge\starter\images\Wireframe.png" width="350" alt="wireframe">
</p>

made using Figma

## License

MIT License

## Acknowedgements

Placeholder images from EdX
Other images from UnSplash.com
