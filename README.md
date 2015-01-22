## Get Fancy

So you've created a coffee website. Now it's time to make sure it's responsive. You'll mostly need to add CSS, but feel free to add HTML if it'll help. You'll also need to add some CSS transitions to create a clearer sense of UX.

## Responsive requirements

* Make the coffee bag images resize as the window resizes

### Below 480px

* Start with a base font size (in your `html` tag) that works best on mobile).
* Nav items should stack vertically.
* Show the coffee bean background image behind the title, not bheind the paragraphs below it.
* One column of header text.
* Don't use any columns for the coffee bags.
* Coffee bags and text should appear side-by-side.

### Above 480px

* Make the base font size bigger, for desktop use.
* Horizontal nav.
* Make nav fixed.
* Header paragraphs to two columns.
* Put the coffee bags in two columns.

### Above 768px

* Don't let the page go wider than 800 or 900px, whatever you feel works.
* Put the coffee bags into four columns.
* Descriptive text should appear underneath the coffee bags.

## Transitions

Create different transitions to spice things up. Include the following. All should happen over time, but you can determine how long for each.

* When you hover over a nav item, give it a border on the bottom.
* When you hover over any coffee item, it should become entirely opaque.
* When you hover over any coffee item, the text size should grow by 150%.
* When you check "Add to cart", give the "Add to cart" text a yellow background and full opacity.
* Pick one other attribute and change it with a transition.
