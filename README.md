Demo : https://ayeshamunawar-profile.github.io/Getaway-Tours/
# Getaway-Tours

It is a website for a tourism company i.e. Getaway Tours. It shows the company details , discount packages and contact
page. This website is developed on HTML, CSS and SASS The project was divided into several sections and I learned many
skills related to javascript while developing each section of the project.

## **Project setup**

1) Download the project or fork it
2) Make sure you have node.js installed to check the version of node.js by running the command bellow
   `node -v`
3) Install all the npm packages used by this project by running the command
   `npm install`
4) Install live server globally so that you can use it for all the projects on your device using the
   command `npm install live-server -g`
5) Run the sass compiler on the terminal by first moving into the sass folder of the project and then running the
   command `npm run compile:sass`
6) Run the live server on your computer using the command `live-server` in another tab in CMD or Terminal

## **Project Notes ( Different stage of developing this project )**

## Front-end

**Skills and Tools I used**

1) HTML5
2) CSS3
3) HCI ,Graphic design , Linea fonts
4) Google fonts
5) Emmet
6) **BEM** for naming classes and structuring the web page
7) **Css grid** I designed for this project and for future use
8) **Think, Build and Architect approach** for developing the individual components and the overall layout
9) **7-1 Pattern** for arranging the sass files into logical folders

**Sections 1: Building the header**

1) The best way to perform a basic reset using universal selector
2) How to set project wide font definition
3) How to clip parts of element using clip-path
4) How to position an element in center and study relative position vs absolute position
5) How to add animations using @keyframes
5) What pseudo-elements are and whats pseudo classes are
6) How and why to use the :: after pseudo - element
7) how to create a creative hover animation effect using transition property

**Section 2: Understanding how css works**

1) How css is parsed
2) How inheritance works
3) How to use different units of measurements like vh vw % em rem or px appropriately
4) css architecture , components and BEM
5) I used the **Think , Build , Architect** mindset to create this project i.e

   a) I thought each part of the project that conveys complete meaning as a component so that my webpage is a collection
   of components connected using a layout . I made sure that the components are reusable across the project.

   b) Then I actually coded the features I planned in HTML5 and CSS3 . I followed a consistent naming convention for
   classes and IDs and variables . I used BEM approaches for naming the classes in CSS i.e Block , Element and Modifier
   approach

        i)   Block is a standalone component that has a meaning of its own e.g. button , menu
        ii)  An element is a part of block that doesnt conveys complete meaning on its own e.g. menu-heading, menu-button-submit
        iii) A different version of a block or an element e.g. button-danger, menu-drinks

   c) For architecture of the project i.e I used **7-1 Pattern** for arranging the different HTML and CSS and sass files
   in folders . We put 7 folder with partial sass files and one main sass file to import all the other files into and
   then compile it into one final css style sheet that the webpage uses. These folders are

        i)    Base: The basic definitions related to the project
        ii)   Components: Each component gets a separate sass file 
        iii)  Layout: The files that defnes the overall layout of the components in a page 
        iV)   Pages: The sass files with code specific to each page 
        v)    Abstract: The sass code that doesnt outputs any css e.g. css variables and mixins 
        vi)   Theme: The different themes of the projecct
        vii)  Vendors: The 3rd - party sass/css files

**Section 3: Using SASS for advance features**

1) Understand basics of SASS. I used scss instead of sass for because its cleaner and allows unit mixing for
   calculations
2) Used Mixins, Functions , Extends , Nested sass , variables , control directives like for loops and conditionals in
   sass
3) Created my own grid system in sass for 1 -4 columns for this project and for future use

**Section 4: Building about section**

1) Thinking about components
2) How and why to use utility classes
3) How to use background-clip property
4) How to transform multiple properties simultaneously
5) How to use outline-offset property together with outline
6) How to style elements that are not hovered while other are

**Section 4: Building features section**

1) How to include and use icon font
2) Another way of creating "skewed section" design
3) How and when to use direct child selector 

**Section 5 : Building Tours Section** 
1) How to add rotating cards effect
2) How to use perspective in css
3) How to use the backface visibility property
4) Using background blend modes
5) How and when to use box-decoration-break

**Section 6 : Building Stories Section**
1) How to make text flow around shapes with shape-outside and float 
2) How to apply filter to images
3) How to create a background video covering an entire section
4) How to use the `<video>` HMTL element 
5) How and when to use object-fit property

**Section 7 : Building Booking Section**
1) How to implement solid color gradient 
2) How the general and adjacent sibling selectors work and why we need them 
3) How to use `::input-placehilder` pseudo-element
4) How and when to use `:focus :invalid :placeholder-shown` and` :checked` pseudo class

**Section 8 : Building Footer**
1) I just applied the concepts I have learned already
2) Use of `display: inline` to make sure the element takes space according to its content and not all the available space 

**Section 9 : Create Navigation**
1) In this section I applied some creative effects to the navigation of the page 
2) I used `Checkbox hack`
3) I created `custom animation timing function` using `cubic Bézier curves`
4) I animated "Solid-color gradient"
5) I used `transform-origin`
6) Use of radial gradient i.e. gradient from the middle part of the element to the outer sides 
7) Use of pseudo-elements `::before` `::after` to create the toggle button and animate it when clicked always set content in the psueo class to something or "" by default otherwise it will not appear on the screen also set the containing element's position i.e. the containing button to relative and the button content to absolute to position it within the bound of the button. They can align to the Center using `text-align:center` property

**Section 10 : Create a pure CSS popup**
1) Built a nice pop-up with only CSS
2) Used the `:target` pseudo-class 
3) Created boxes with equal height using `display: table-cell` in the children element and `display:table` in the parent element 
4) Created CSS `text-column`
5) Automatically Hyphenated words using `Hyphens`
6) Navigate to the part of the page by clicking a link simply put in `href="#section-name"` the id of the html element you want to navigate to the element to move to is called as target and the link is called as an anchor

**Section 11: Make the website responsive**
1) I used Desktop first approach to create the website i.e I created the website for desktop first and then shrunk the design for smaller screens
2) I used the most popular screen sizes from the internet and grouped them together based on device type thus defining breakpoints for my project 
3) The breakpoints I descided are `Phone only (0-600px)` , `Tablet Portrait : 600px - 900px` , `Tablet Landscape : 900px - 1200px ` , `Desktop: 1200px - 1800px ` , `Bigger Desktops : >=1800px`
4) I used Max-with for media queries for Desktop first approach (min-width is used for Mobile first approach)
5) I used a powerful SASS mixin to write all media queries 
6) I used `@content` and `@if` SASS directives
7) I started using media queries starting from the base and typography and them to the layout like header footer  grid 
8) Then I wrote media queries for the page layout and then for the components

**Section 12: Use responsive images**
1) Make images responsive for making the website responsive and improving web performance. The purpose behind responsive images is to serve the right image to the right screen size and device in order to avoid downloading unnecessary large images on the smaller screens 
   1) One way of doing it is resolution switching i.e. decrease image resolution for smaller screens 
   2) Density switching special type of resolution switching eg. for 2x screen (2 pixels to show 1 pixels of design) show high resolution image with double resolution and for 1x screen low resolution e.g. half the image resolution. decrease pixel density i.e. no of pixels per inch or cm while the dimensions of the image remains the same 
   3) Third way is art direction to serve different image for the different screen or cropped image
2) How to use the `srcset` attribute on the `<img>` and `<source>` elements , together with density descriptors 
3) How and why to use the `<picture>` element for the art direction
4) How to write media queries in HTML using `<picture>` `<source>` and `<img>`
5) How to allow the browser to decide the best image to download using the `srcset` attribute width descriptors and the `sizes` attribute of the `<img>` element 