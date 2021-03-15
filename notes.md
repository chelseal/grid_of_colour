challenges:
- fitting the svg to the background neatly
- CSS grid formatting

learnings:
- remove unnecessary wrapping HTML tags to reduce white space issues with svg
- use CSS transform or cx (pushes shape east (left)), cy (pushes shape south (down)) coorindates to orientate an svg

SVG shapes:
circle: <svg height="150" width="150"><circle cx="75" cy="75" r="75" fill="var(--orange)"/></svg>
quarter circle: <svg height="150" width="150"><circle r="150" fill="var(--orange)"/></svg>
square: <svg width="150" height="150"><rect width="150" height="150" fill="var(--orange)"/></svg>

building flow:
- find a grid example online 
- play around with this grid design using inspect tool
- set up grid container
- print one svg to screen
- print 24 coloured svgs to screen
- code colour palette from design
- create CSS variables for colour palette
- change random colours to CSS variables
- change placeholder rectangles to circles
- change placeholder rectangles to quarter circles
- orientate quarter circles: use cx, cy position to change where the circle starts within the svg.
- add design background colour
- add background colour