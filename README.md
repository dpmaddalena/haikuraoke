# haikuraoke

a full-screen visual poetry performance program

## possible names

- Haikuraoke
- Haikubox


## overview

Application for live visual presentation of haiku and other short written pieces as accompaniment to live music performance. An audience sees a full-screen, live-editable, image of typing on-screen as music plays. The typing is not pre-recorded, but performed, so that as the band plays/improvises, the poet types out a poem on screen, correcting mistakes as she goes, changing fonts and colors with keyboard commands on-the-fly, basically controlling the app like a visual musical instrument, playing with the band. 


## features

- full-screen presentation-style (app fills external monitor, so poet can view reference material on laptop screen while audience sees only the application via projector, old TVs, etc.)
- configuration via config.txt (no need for a UI), for 
	- font face, size, color
	- background color
	- custom combinations triggerable by keyboard shortcuts
- keyboard commands for 
	- clear screen
	- word animations
	- color-shifts
- ability to load a video as background image
- ability to load a txt file for live editing/erasure
- nice-to-have a mac and linux version (one use-case is to run this on a raspberry pi)



## problems to solve

How to ensure that lines will not break in the wrong place? The poet-performer should, of course, know that a certain line-of-a-poem will break when using Helvetica above 28 points, eg, but maybe the program adjusts on the fly to reduce font-size if a line goes to the edge of the window and is about to break? That's probably too much for v.1, but the point is that each line of poetry is sacred and has to only ever be on a single line of the screen. 
