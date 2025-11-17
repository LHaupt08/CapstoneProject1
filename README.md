# Project Assignment: HTML & CSS Capstone
(delete everything in parenthesis after you have finished(including this line 😜))

## Group Members
#### - Elizanna Hahn
#### - Lukas Haupt
#### - Dominic Bass

# Title of Website: CollectaMedia
#### (use in title tag, pretend it's your domain name, do not include https or .com) <- Delete this line

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
- Header Font Size 

## CSS Ruleset 

### Header Classes

- .main (ul): Original purpose was to state a difference between the main ul and submenu uls, but we were not able to get that far. In its current state, it mainly sets how the lis are laid out, defines the ul's flex, and dissapears at a certain screen size, only to appear when hovering over the navicon.

- .horizontal, .horizontal2 (nav): These two are basically the same thing, the copy existing to make sure the header (which has a fixed position) does not cover up other things on screen. Otherwise, it just uses the same display and flex flow as ul.main, due to the ul not being the only item in the header (note: horizontal2 dissapears on mobile layouts, as the header has a relative position there.)

- .navicon, .logo (div): Containers for the navicon and logo. Mainly made so the space between the logo and navicon in mobile layouts would be able to be spaced to the way we wanted. The nav icon does not display on screen sizes above 768px, but when hovered over on screens smaller than that size, the ul will appear.

(Include every class name, what it applies to, and what its purpose is)

(You do not need to include every ruleset, only the ones that use class names (REMEBER you do not use id names for CSS))

- (EXAMPLE: ClassName: for list elements that need to be aligned left of an image: font size 1rem, color #FFFFFF, bullet style, alignment: left etc. )