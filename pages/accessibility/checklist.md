---
layout: page
title: Checklist
---
This checklist helps developers identify potential accessibility issues affecting their websites or applications. It’s broken down into three sections of decreasing importance: A, B and C. Please check and address these issues in the order in which they appear.

For more detail on accessibility standards, please see WCAG2.0 AA

A - Critical issues that will cause serious problems and/or stop most users of assistive technology from using the site
B - Issues that may cause problems or increased frustration for certain users
C - Minor issues that will cause problems or frustration for a small number of users
It is important to note, while B and C are noted as less critical, they are still required to be truly 508 compliant. This checklist should be used as a reference for development and is not a substitute for compliance checks by a section 508 coordinator.

A - Critical
Site is keyboard accessible
All interactions can be accessed with a keyboard
Site is free of keyboard traps
The keyboard focus is never trapped in a loop
All form inputs have explicit labels
All relevant images use an img tag
All images have alt attributes
Multimedia is tagged
All multimedia has appropriate captioning and audio description
Text has sufficient color contrast
All text has a contrast ratio of 4.5:1 with the background
B - Less Critical
Site never loses focus
Focus is always visible when moving through the page with the keyboard
Tab order is logical
Form instructions are associated with inputs
Site doesn’t timeout unexpectedly
Identify elements that may “timeout” and verify that the user can request more time
Tables are coded properly
Tables have proper headers and column attributes
Headings are nested properly
Heading elements are nested in a logical way
C - Minor
Frames are named
All frames have a name element
Flashing elements are compliant
Elements that flash on screen do so at a rate of less than 3 Hz
Language is set
The language for the page is set
The language for sections on the page that differ from the site language are set
CSS is not required to use the page
The page makes sense with or without CSS
Links are unique and contextual
All links can be understood taken alone, e.g., ‘Read more - about 508’
Page titles are descriptive
Required plugins are linked on the page
