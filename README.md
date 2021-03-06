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
