# Sass practice

## Step 1: nesting

Use Sass to nest all rules.

You'll need to learn a certain trick for using psuedo-selectors in nested Sass rules. See if you can Google it.

## Step 2: colors

First define a variable for your dominent color. You can use the color currently being assigned to `<a>` tags. Then, use one of the color function you've learned to alter the color of links when being hovered.

Then, define an accent color. (Maybe use a brown from the coffee image.) Use that new variable for the `ADD TO CART` text. And then add a hover state to all the coffee flavors and use a lighter version of that brown for a background color when using hover.

## Step 3: imports

You'll notice that I renamed `css/reset.css` to `css/_reset.css`. This file is generated via `scss/_reset.scss`. I renamed it for a reason that has to do with a feature of Sass that allows for importing other files. See if you can figure out how to import that file at the top of our `screen.scss` file. When you do, you'll no longer need to link to `_reset.css` at all.

## Bonus: math

Sass has very strong support for math. If you finish before other people, play around with some of the numbers in the CSS file by replacing them with variables and math.
