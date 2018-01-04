

http://rockdirector.github.io/index.html


# Frontend Challenge: BusyBus

This was indeed a challenge, primarily in trying to understand and work around the quirks of the box model in the dimensions of a small device screen.

I continued with the look and feel of my last iteration of BusyBus, starting with the same element positions, typefaces and colours. I took the liberty of exporting flat image slices of the navigation/map and iOS tab bar models from my Sketch mockup.

To retain the border structure from the scheduling sliders of my mockup, I had to learn how to use pseudoclasses to enable different origins between items to heighten legibility and reflect current iOS design patterns.

The new route direction headings from the provided asset document added complications to the style. I ended up adapting an existing iOS design pattern of caps on a light background to clarify and reinforce the understanding of the more complex information structure.

I also had to learn how to position the nav and tab bars as different divs/structures using fixed and absolute position tags and adding z-heights.

Then once scrolling was added to the bus-listings child section, the scrollbars on my desktop browser changed the margins and broke the design. I struggled with first trying to remove the scrollbars in CSS code, before realizing that I needed to change my MacOS general settings. In iOS there will not be scrollbars, but I am accepting that this may not display correctly on a desktop browser.

Accessibility testing revealed a number of unanticipated errors, including a missing language definition, a missing page title (admittedly a lazy oversight), and no alt text on the image files (less relevant, since they are just temporary placements for mockup). Wave also noted insufficient contrast in the grey text against the light grey background (which I based upon Apple's Contacts App design pattern, but increased to 8.59:1, enough to pass AAA.

Finally, setting up the GitHub page was self-explanatory.

I look forward to your feedback!

Dan Bryk
