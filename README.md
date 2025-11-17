# Project Assignment: HTML & CSS Capstone

## Group Members
#### - Elizanna Hahn
#### - Lukas Haupt
#### - Dominic Bass

# Title of Website: CollectaMedia
#### CollectaMedia:

## Purpose of Website
 This website is for gamers and collectors who are tired of the high prices they are charged when trying to enjoy their hobbies. No having to deal with the extreme upcharges that other websites have. We have much to offer, and all at an affordable cost.

## Target Audience
- Age Group: Late Teens (16-45)
- Sex: Any
- Interests: Gaming, Collecting

It would offer a place to endulge in their hobbies at an affordable cost. It could also introduce new interests.

## Assigning Tasks
Elizanna: Video/Audio, Shopping Form, "Recent Games"
Lukas: Header, Logo, "Video Game of the week", "Popular Games"
Dominic: Picking out items for catalogue, Catalogue, Footer

## Website Layout

## CSS Themes
### Fonts and Colors
- Font for Headings: Jersey 10, https://fonts.google.com/specimen/Jersey+10
- Font for Paragraphs: Montserrat https://fonts.google.com/specimen/Montserrat
- Background Color: #637463
- Font Color: #f1fef5
- Contrast Ratio: 4.8
- Additional Colors: #2b342b(1-6)
- Paragraph Font Size: 1 rem
- Header Font Size: clamp(1.5rem, 2vw, 2rem)

## CSS Ruleset 

### Header Classes

- .main (ul): Original purpose was to state a difference between the main ul and submenu uls, but we were not able to get that far. In its current state, it mainly sets how the lis are laid out, defines the ul's flex, and dissapears at a certain screen size, only to appear when hovering over the navicon (has a background color of #637463, and a border of black with 5px)

- .horizontal, .horizontal2 (nav): These two are basically the same thing, the copy existing to make sure the header (which has a fixed position) does not cover up other things on screen. Otherwise, it just uses the same display and flex flow as ul.main, due to the ul not being the only item in the header (note: horizontal2 dissapears on mobile layouts, as the header has a relative position there.)

- .navicon, .logo (div): Containers for the navicon and logo. Mainly made so the space between the logo and navicon in mobile layouts would be able to be spaced to the way we wanted. The nav icon does not display on screen sizes above 768px, but when hovered over on screens smaller than that size, the ul will appear.

### Index Classes

- .dontbreakheader (div): Envelops everything on the index, setting the sections and marquee as a row (but the sections are in their own div).

- .notpopular (div) [I don't know why I named it this]: The area taking up 75% of the index, and holds the sections. Displays them in a column. On smaller screens, it has a width of 100%.

- .vgow (section): holds the content for the Video Game of the Week box. It has a linear gradient of: ((180deg, #384238 2%, #637463 25%), but all sections have that). It displays its content as a row (the header, image, and video being displayed on one side, and the description and audio on the other side.). Other smaller things of note are it's width of 100% (of div.notpopular), margin of .2rem, padding of .5rem, and finally a border radius of 10px.

- ."col-" (div): Makes sure both "col-" divs are set as columns.

- .col-1, .col-2 (div): sets flex size for the columns; Their size changes on mobile. .col-1 holds the header, image, and video, while col-2 holds the description and audio.

- .gameMedia (div): holds the image and video, and displays it as a row, with their items aligned in the center of the cross axis (horizontal axis). It has a padding of 5px, a top and bottom margin of 0px, and a left and right margin of 2px. Finally, it has a height of 100% (if I recall correctly, it was not originally reaching the bottom without it).

- .recents (section): Displays the h1 and div.imgbox in a column, with a width of 100%, a margin of .2rem, and a padding of .5rem.

- .imgbox (div): Holds the recent games, displaying them in a row, with a width of 100% (to take up all the space in the recents section). On smaller screens, it displays the items in a column.

- .img (div): original intentions were possible description (or title) to be added with the images, but that was never done, but a different purpose was found with them: makking a more flexible way to space the images out. It also aligns the content to the center of the main axis.

- .popular (section) [There is no class name for the marquee]: The second column of the index page. It displays the popular items in a marquee, scrolling along the page. It has a width of 30% (don't remember the total width is over 100%, but not changing it now), a margin to the left of 20px (giving the marquee space to be independant from the main content), a border radius of 20px, and a background color of #202722. something extra to note, is that the marquee it contains has a fixed position (as it defines it's scroll height, as well as it's general height in the marquee element. While I could make the section fixed as well, it would be a lot more trouble to deal with than its worth). Additonally, on smaller screen sizes, this does not show up.

- .item (div): Holds a description list term (item image) and defenition (item name), displayed in a row. Text is aligned to the center, and the divs have a top and bottom margin of 10px.

### Payment Classes (note that most classes would be ids if js was used.)

-  .Customerinfo (form): The form's class, with a background color of #637463. It is a block, with a width of 95%, a top and bottom margin of .2rem, and an auto left and right margin. It also has a padding of .5rem, and a border radius of 10px. It's margin changes on smaller screens, not having a top and bottom margin, but still having a automatic left and right margin.

- .buttons (div): Contains the submit and reset buttons. It has a white border of 1px, a top and bottom margin of 2rem and a auto left and right margin. In addition, it has a padding of .5rem, centers it's content along the main axis, and displays its content in a row.

### Catalogue Classes

- .catalogue (div): Mainly made for making sure the catalogue's css page did not mess with the header, it displays each catalgue div (containing two items) as an inline-block with a margin of 4%. On smaller screens, this margin is changed to 5%.

#### All other changes are not directly through class, but affect the actaual element.