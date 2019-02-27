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
