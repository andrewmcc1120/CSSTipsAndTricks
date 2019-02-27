# CSSTipsAndTricks
Here are some tips and tricks that I have found useful, especially in my current position.

## Font Sizes
Choosing the correct font size can actually be pretty difficult depending on how large the screen is that the user is viewing your app. Luckily,
CSS has a ton of options on how to size your text.

1. My personal favorite, vh and vw, takes a percentage of the viewport height(vh) or viewport width(vw). So, if you were to say 10vh, that is 10% of the
viewport width. (viewport meaning the screen that the user is viewing the app from). So, a 1920x1080 screen will render 10vh as 108px font size.

2. A very popular option is rem and em. What they actually do is this: em is a relative size that compares the text directly to the nearest parent, while rem 
goes all the way back to the html ROOT. Most browsers default html text to 16px, so if you say 2rem that is going to render text as 32px in size.

Obviously, you can size your text using pixels, points, and percentages as well but they are not the best options especially when being responsive is an absolute must.

## Margin and Padding
Margin and padding were pretty elusive concepts to me at first, but they are an absolute must in creating great designs and having everything work well together. 
Consider them this way: Margin is on the outside of the element you are adding it to, padding is on the inside of the element you are adding it to. If you have two 
divs next to each other, margin will push them away from each other(given there is enough space on the page) and padding will push the item inside the div away from the edges of that div.

Margin and padding can also be measured much like font size but being specific is usually the best option i.e. points, pixels, em, rem.s
