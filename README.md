#Bookmark Landing Page

## The challenge

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Built with

- HTML
- CSS

### What I learned

This exercise might be the second toughest one I had to deal with. I had to get back home and spend the rest of the day still trying to get everything as right as I could while trying to follow the instructions and the design which I hoped I think I got close to it. I better my knowledge again on Viewport and design break which caused me some serious headache. Also I tried my best to reproduce the background blue design using the Z-index of course but I couldn't place it right I used both Online content and an AI to "guide me" not do it for me. I tried using Javascript for the form validation and other little stuff but my knowledge wasn't broad enough to use by myself and understand how it works I preferred not using it at all which caused some trouble on my page. I also used div a lot which makes my code imperfect cause it doesn't respect the semantic but I wanted to have the design first then modify it with time. This is a code I need to redo and perfect it before I could be satisfied of my work but for the general design I think it's almost perfect but without using Javascript I was stuck and some parts of my code is dead so I'll correct it after finding a solution without using Javascript as soon as possible.

### Continued development

It might be today that I realized that I've never really used SVG before and it was a rediscovery on how it is so different than regular images to use so I think I need to read on that too. Although I understand how Z-index function I could really implement it perfect today so I also need to read on that.
I also didn't really do themes because I didn't understand if I was to leave a dead CSS of a different palette of colors for the different themes so I prefered not taking the risk. I still couldn't produce a perfect design because I lack Knowledge on many aspects. Many little details which sums up and at the end my work is always backwards. I'll try my best for the rest. Also I realized that I always use way too much time on this exercise which also proves that I still have many things to learn, I spend time reading instead of coding because I lack many notions and it makes me slower.

### Useful resources

[https://www.w3schools.com/]
[https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Containment/Container_queries]
[https://modern-fluid-typography.vercel.app/]

### AI Collaboration

I uesd Claude to help me implement the background blue design and also tried it for Javascript which I finally deleted because I didn't understand it's function thus making my exercise incomplete because of that.


### Updates:
-- Added 2 theme blocks: [data-theme="dark"] and [data-theme="contrast"]. -- Fixed every dead widget and js free.

Theming update
Replaced the two lone --bg/--text overrides with a full set of role tokens (--surface, --text-muted, --border, --chrome-bg,--chrome-text) so every component repaints, not just the page background.
--Added a real toggle: three radio buttons in the header, wired with :has(), no JS. An explicit choice always beats the system default.
--Added @media (prefers-color-scheme: dark) so the site opens in dark mode automatically if the OS is set to dark, until the visitor picks a theme.
--Added a sepia theme as a fourth option, mostly to prove the token setup actually works everywhere.
--Added the missing success state on the email field (same :has() pattern as the error state, just :valid instead of :invalid).