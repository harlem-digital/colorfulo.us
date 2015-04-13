#colorfulo.us

##Inspiration

colorfulo.us is inpired by:

* Colorrrs: http://hex.colorrrs.com/
* 147 Colors: http://www.colors.commutercreative.com/

##Introduction.

The problem I often have as a developer is being able to name things. So I often am googling hex values to see if the color does have a color name, and possibly doing a separate search to see if it has an rgb value for various reasons.

The beauty of Colorrrs is that you have the ability to enter a hex value or rgb value and be able to get it's counterpart. The awesome part of 147 Colors is that you're able to find all of the CSS Color Names. What would be awesome is if you could combine these two tools to do one search and find all of this information.

####Example

If I search for `ffffff`, I want the returned values to be:

* Hex Value of `ffffff`.
* RGB Value of `rgb(255, 255, 255)`.
* CSS Color Name of `white`.

If I search for `fff`, I want it to return a list of all possible values:

* Hex Value of `fff8dc`, RGB Value of `rgb(255, 248, 220)`, CSS Color Name of `cornsilk`.
* Hex Value of `fffaf0`, RGB Value of `rgb(255, 250, 240)`, CSS Color Name of `floralwhite`.
* Hex Value of `fffff0`, RGB Value of `rgb(255, 255, 240)`, CSS Color Name of `ivory`.
* Hex Value of `fff0f5`, RGB Value of `rgb(255, 240, 245)`, CSS Color Name of `lavenderblush`.
* Hex Value of `fffacd`, RGB Value of `rgb(255, 250, 205)`, CSS Color Name of `lemonchiffon`.
* Hex Value of `ffffe0`, RGB Value of `rgb(255, 255, 224)`, CSS Color Name of `lightyellow`.
* Hex Value of `fff5ee`, RGB Value of `rgb(255, 245, 238)`, CSS Color Name of `seashell`.
* Hex Value of `fffafa`, RGB Value of `rgb(255, 250, 250)`, CSS Color Name of `snow`.
* Hex Value of `ffffff`, RGB Value of `rgb(255, 255, 255)`, CSS Color Name of `white`.
* Hex Value of `ffff00`, RGB Value of `rgb(255, 255, 0)`, CSS Color Name of `yellow`.

The same would happen if I searched for a rgb value or css color name.

##Functionality

###Search

Searching is the primary tool. We should be able to:

* Instantly provide results with each keystroke.
* Be able to find hex, rgb, and css color names.

###Save

Save a color or color palette would be awesome.

* Save a color to a list with it's hex, rgb, and color name.
* Should be able to save these values via local storage.

###Export

Export a color list.

* Export a color / list with default SCSS Variables.
* Export a color / list with user defined SCSS Variables.
* Export a color / list in a SCSS List.
* Export a color / list in a JS Object.

###Clear

Should be able to remove that list of colors that have been stored in local storage.

##Enhancements

###Add 500+ Colors

Add in the ability to search for even more colors that are generic. This would be a seperate feature.

####Resources

* http://cloford.com/resources/colours/500col.htm

###Add Causes

Add the ability to search for Causes or see if colors are associated to causes. There have been some attempts to begin compiling a list of this information. It all started with some work from [Tobias Wright](https://github.com/tobiaswright). We'll need to clean this up, and check to make sure these values are legit. I wonder if there are any legal implications to getting the color 'wrong'. Thinking about branding, etc.

####Resources

* https://github.com/tobiaswright/awareness-color
* https://github.com/whoiskenjackson/color-dictionary

###Mobile / Web App

Pure geekery. What if we could either save to home screen and have this run offline? Or create a separate app entirely and have this be downloaded from an app store. Desktop, Mobile, etc. Just brainstorming.