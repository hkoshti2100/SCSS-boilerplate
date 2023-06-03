<div align="center">
  <img src="https://github.com/hkoshti2100/scss-boilerplate/assets/135125859/4c6d356d-5eef-4231-97ab-ab78605f415d">
</div>

# SCSS BOILERPLATE

Welcome to a very simple yet probably very helpful repository, set up as a boilerplate template to help with basic Web Development using nothing but HTML, CSS, JS and a powerful implementation of SCSS.

The aim of this repository is to get started with a very helpful template anytime you want to create a basic website using simple HTML, SCSS and JS.

- [FOLDER STRUCTURE](#folder-structure)
- [UNDERSTANDING THE FOLDER STRUCTURE](#understanding-the-folder-structure)
  - [*index.html*](#indexhtml)
  - [lib](#lib)
  - [pages](#pages)
  - [resources](#resources)
  - [scripts](#scripts)
  - [styles](#styles)
    - [*main.scss*](#mainscss)
    - [components](#components)
    - [global](#global)
- [FINISHING THOUGHTS](#finishing-thoughts)

# FOLDER STRUCTURE
- *index.html*
- lib
- pages
- resources
	- files
	- fonts
	- icons
	- images
	- videos
- scripts
- styles
	- *main.scss*
	- components
	- global
		- *_animations.scss*
		- *_classes.scss*
		- *_elements.scss*
		- *_fonts.scss*
		- *_global.scss*
		- *_ids.scss*
		- *_index.scss*
		- *_media.scss*
		- *_mixins.scss*
		- *_variables.scss*

# UNDERSTANDING THE FOLDER STRUCTURE

## *index.html*
Obviously, the HTML file containing the document of the Home Page of the website.

## lib
This folder will contain any external package or library that will be installed to help with the development process. For example, ***normalize.css***, ***jquery.min.js***, etc.

## pages
This folder will contain HTML files of other pages of the website like ***About Us***, ***Contact***, etc.

## resources
This folder will contain web media resources like **downloadable files**, **font files**, **SVG icons**, **images**, **videos**, etc. which will all be contained in their own folders in a grouped manner.

## scripts
This folder will contain our own **JavaScript files** to add interactivity and functionality to the website. Different scripts can be saved as separate ***.js*** files to keep our **JavaScript code** modular.

## styles
Last but (definitely) not the least, this is the most important part of this boilerplate code. This folder contains ***.scss*** files for fast and efficient usage of **CSS** by using all the features of **SCSS**. This folder is further structured down as follows to keep our **SCSS code** modular:

#### *main.scss*
This file will contain the main **SCSS styles** to be added to the **Home Page** (or the **Landing Page**), whose HTML file is located at the root of this repository as ***index.html***.

#### components
This folder will contain **partial SCSS files** ( beginning with an underscore, e.g., ***_header.scss*** ). Each of these partial SCSS files will contain the styles for styling one specific component.

These files can then be added to the main SCSS file by simply using `@use _header.scss;` in the base SCSS file for the web pages.

This approach fives us the advantage of keeping our SCSS code clean, modular and reusable.

#### global
Now, this is the backbone of the **SCSS Hierarchy**. This folder contains partial SCSS files, each with their own very specific usage. These files are as follows:

| Files | Description |
|-------|-------------|
| *_animations.scss* | contains all CSS animation declarations. |
| *_classes.scss* | contains very commonly used class declarations, e.g., `.border-green`. |
| *_elements.scss* | contains globally styled elements to maintain a consistend theme. |
| *_fonts.scss* | contains simple font import URLs and/or `@font-face` rules. |
| *_global.scss* | contains CSS Reset declarations. |
| *_ids.scss* | contains very specific id selected properties to style unique elements. |
| *_index.scss* | contains only the `@forward` rules to forward all these global SCSS modules in order to be imported in other SCSS files like *main.scss* and *_header.scss*. |
| *_media.scss* | contains media queries to achieve responsive UI Design. |
| *_mixins.scss* | contains SCSS mixins to be included in other SCSS files. |
| *_variables.scss* | contains both CSS and SCSS variables to be used throughout the website. The variables are configured in such a way that even after using SCSS variables, we end up with CSS Custom property values in the output CSS file. |

# FINISHING THOUGHTS
I created this repository to officially begin and document the beginning of my web development journey. I intend to get very proficient with not only code, but also design patterns and best practices.

Certainly, this wil not be perfect and I will keep pushing changes to this repository as I learn new things.

If you liked this repository, please leave a star for me and always feel more than welcome to submit your pull requests if you have better structuring and modularizing solutions to such small projects.
