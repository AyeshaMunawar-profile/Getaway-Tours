# Getaway-Tours
It is a website for a tourism company i.e. Getaway Tours. It shows the company details , 
discount  packages and contact page. This website is developed on HTML, CSS and SASS
The project was divided into several sections and I learned many skills related to javascript while developing each 
section.

## **Project Notes ( Different stage of developing this project )**

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
5) I used the Think , Build , Architect mindset to create this project i.e
   
   a) I thought each part of the project that conveys complete meaning as a component so that my webpage is a collection
      of components connected using a layout . I made sure that the components are reusable across the project.
   
   b) Then I actually coded in HTML5 and CSS3 . I followed a consistent naming convention for classes and IDs and 
      variables . I used BEM approaches for naming the classes in CSS i.e Block , Element and Modifier approach
       
        i)   Block is a standalone component that has a meaning of its own e.g. button , menu
        ii)  An element is a part of block that doesnt conveys complete meaning on its own e.g. menu-heading, menu-button-submit
        iii) A different version of a block or an element e.g. button-danger, menu-drinks
   c) For architecture of the project i.e I used 7-1 Pattern for arranging the different HTML and CSS and sass files in 
      folders . We put 7 folder with partial sass filed and one main sass files to import all the other files into a compiled css style sheet.
      These folders are 
        
        i)    Base: The basic definitions related to the project
        ii)   Components: Each component gets a separate sass file 
        iii)  Layout: The files that defnes the overall layout of the components in a page 
        iV)   Pages: The sass files with code specific to each page 
        v)    Abstract: The sass code that doesnt outputs any css e.g. css variables and mixins 
        vi)   Theme: The different themes of the projecct
        vii)  Vendors: The 3rd - party sass/css files

**Section 3: Using SASS for advance features**
1) Understand basics of SASS. I used scss instead of sass for because its cleaner and allows unit mixing for calculations 
2) Used Mixins, Functions , Extends , Nested sass , variables , control directives like for loop and conditonals in sass 
3) Created my own grid system in sass for 1 -4 columns for this project and for future use 