# SASS 

SASS is abbreviation for Syntactically Awesome Style Sheets. It is CSS preprocessor. Basically, it is much more to CSS i.e. CSS with superpowers.

SASS --- for CSS

SCSS is same but we called it that for CSS3. Extension to filea is ".scss"

## Why SASS?

As for beginners point of view, it gives removes browser compatibility issues. If we add a property to scss file, its browser compatibility prefix will be added automatically to css file.

Also it time saving because, repeated code is eliminated wih using SASS, i.e., we gie a name to line of codes and include it whereever it is needed.

## SASS fetures / superpowers
 
1. Operators  - can use operators eg. font-size: 3rem + 1.5rem;

2. Variables  - we can use variables also to give values to property eg. $font_s: 1.5rem; -----> font-size: 3rem + $font_s;

3. Nesting  - code section with a code section.

4. Mixin and include - properties which are repeatedly used can be for mixin, those properties can be used later whenever, and wherever needed by including its name. 

5. Partials and import - you can make seperate file for each css section, eg. variables in different file, mixin codes in different file.

## Note: you can use scss/main.scss for reference. I have added comments to help you getting what is really happening. You dont have to make mapping file and css file. It will be automatically be created.

## Using SASS in Visual Studio

You have to install a plugin "Live SASS Compiler", after it gets installed you will see "Watch SASS" button at status bar.

Make index.html file.

Make scss/main.scss file.

Write your code in index.html (you can use my sample code)

Write proprties in main.scss (refer to my main. scss)

Press "Watch SASS", you have to press it only once, new code will be compiled automatically. 

This will make mapping file and css file. You can see css file, you will see what I was talking in why SASS.

Don't forget to add reference of css file (not scss file) to index.html to reflect css properties.

Enjoy!!
