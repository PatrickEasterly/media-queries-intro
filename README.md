# What is "responsive web design?"

- 800 X 600 is a thing of the past! 
- Different screens have different resolutions (number of pixels) and densities (number of physical pixels per "screen pixel")
- Te technique is to change the layout and serve different images based on the user's screen resolution/density

# What are media queries?

- They're like if-statements for your CSS 
- The if conditions are based on the viewport
- You can also check other things like orientation, screen density, etc. 

# What is a viewport?

- It's the thing you're looking through to see a web page
- You can scroll it, you can zoom

# What are breakpoints? 

- The if-conditions for media queries
- A threshold where a media query is triggered

# Where should I set my breakpoints? 

- approach #1: Goldilocks (small, medium, large)
- approach #2: depends on wherever the design starts to look crappy

# What are three ways of handling responsive images? 

- #1. Background images in CSS (background-size: cover)
- #2. Use srcset to specify different images for different resolutions
- #3. Use <picture> for differently cropped images
