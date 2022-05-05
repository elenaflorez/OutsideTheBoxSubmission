
# Front-end Web Design: Project 2

This website was an opportunity to use the responsive coding techniques developed during this course in a creative and unique way. 

## Concept
The aim of this assignment was to tell a story through change. Responsive websites are able to respond and change, and so I built the story around the size of the page itself. I drew upon some experiences my family had moving from a small apartment to a house, and how some hobbies of ours bloomed with more space. So I decided to make a bit of a children style/reflection on space and its effect on hobbies and experiences. 

The way I told this story was through the text and having the images depicting the story change in size and display from a tower (a child-like depiction of an apartment) to a larger house. 

## GitHub and Static Site Generator
I started the website without using the static site generator at first, as I was more comfortable with the previous structure. (You can see previous commits here: https://github.com/elenaflorez/Outside-the-grid).

This meant that I needed to adapt my website to the structure of the static site generator, which was a challenge at first. In particular the way I was handling the text and images didn't carry across. Once I furthered my understanding of the static site generator as a framework from which other content can be placed, I was able to restructure and replace my website code into the static site generator. 

## Grids
This project demanded the use of both flex-grids and normal grids. I was able to use a flex-grid for the tower, as they're easy to work with and create a natural tower shape with the column orientation. I initially struggled with the flex-grid to try to make it create the house shape, but I found that if I changed the style of the house to a normal grid I was able to specify the number of columns and have the items arranged properly for the house. 

Putting the roof on was a challenge also. Initially I was able to place the roof as another item in the flex-box for the tower, but that carried over poorly to the house as it interpreted it as another room. I found by separating the house and roof into separate objects, wrapping them both in a 'structure' which was a single grid, I was able to keep the roof consistently on-top of the items and have it sized properly for both the tower and the house. 

## Spacing
I wanted items to be displayed neatly with proper spacing, and initially I was using px margins but that made the spacing quite different on the mobile. By using % spacing for the margins and gaps, I kept things neat and consistent between the screen sizes. 

I also wanted the house/tower to be indented from the sides, and found by using % sized columns in the 'margin' class I could get a consistent margin without having to specify the margins between sets of objects. 

## Images
In Project 1 for this course I struggled with image sizing, and this project relied on images to work. Initially I ran into my previous issues, having images sized larger than their containers or not keeping their width to the size of the screen. I found that keeping images as their own objects and styling their width directly within the grid kept them behaving properly and consistently. 

I also wanted to have different images for the tower and room. I experimented with having the house and tower swap entirely, but I found that given the they share a lot of styling it was easier to have the 'house' change grid style between the tower and house size and make the rooms themselves appear and disappear. 

Another unique aspect of the site is that all the images are my own hand drawn illustrations. This was a fun part of the project to include. 

## Text
The styling of the text was important for the concept, so I found a text style that looked like a marker for a children's book. In addition, I had to re-size the text for mobile so it remained easy to read. Luckily the text was already defined in em, so I could just change the text size in the body

## Reflection
Given more time the main addition I would have made to the site is more styling. I'm happy with the interactivity and responsiveness of the site but given the style was aiming to be childish I think more colour would have been effective. 

Overall this was a fun and satisfying website. I was able to use the responsive skills from the previous website in an interesting way that told a story through the size of the screen. The static web generator was an initial challenge but then straightforward and clearly valuable. 

## Resources

https://snipcart.com/blog/11ty-tutorial
https://www.sitepoint.com/getting-started-with-eleventy/
https://www.tutorialbrain.com/css_tutorial/css_font_family_list/
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout
