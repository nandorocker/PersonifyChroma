Chroma Special Effects
===

Anything in **quotes** should be considered a codename and needs to be renamed before release. Codenames can be anything we like. Final name must be approved by legal.

Screen gestures are additive, so even if two toggles share the same gesture with different results, it shouldn't conflict; those results should happen simultaneously when those toggles are turned on.


## "Kung Fu"

### Abstract

Inspired by old Kung Fu movies, in the style of Bruce Lee and Mortal Kombat special effects, by default actor motion leaves behind a trail that is colorized, and slowly fades out.

Variations should highlight:

- Mystery
- Surprise
- Mysticism
- Superpowers

### Interactions

#### Toggles

1. "Drama"
	- Activates color & contrast effects on background and foreground
2. "The Snake"
	- Sets trails in motion towards a direction
3. "The Dragon"
	- Trails scale outwards from user, growing almost to the size of screen and fading away
	- If "dragon" and "snake" are active, 	trails should grow AND move

#### Screen Gestures

- "The Snake"
	- Tapping anywhere sets the direction of trails
	- Double-tapping cycles between different trail speeds (1, 2, 3, 4, pre-defined by us)
- If "The Dragon" is enabled
	- Tapping sets how far trails should grow to
	- Tapping and holding should accelerate trail speed (slowly) until it gets so fast that it's a solid color around actor

#### Actor Motion

- Color shift
	- By default, trail color should be XXXXX
	- The more motion, the more trails grow toward YYYYY
	- This variation should have a tiny bit of delay, so it matches the "trailing" feel of the animation
	
	
## "Clones"

### Abstract

Like a 90s video, this effect will leave a trail of radical on its wake. It duplicates the user's current frame at random parts of the screen, with slightly different sizes and different effects applied.

Variations should highlight:

- Radical
- 90s cheesy videos
- Slightly over-the-top aesthetics

### Interactions

### Toggles

1. "Color cycle"
	- Cycles through a fixed color palette at a fixed speed
	- Colorizes each stamp with the current palette color
	- Palettes should be pre-defined, randomized with each activation
2. "Squish n' Stretch"
	- Stamps will vary in width and height
	- Values randomized at every stamp
	- From 0.5x to 1.5x
3a. "Dancing clones"
	- All stamps will travel across screen in one of 3 different patterns (all stamps at once, one pattern at a time):
		- Diagonal
		- Horizontal
		- One column up, one column down
3b. "Buzzing clones" (alternative)
	- All stamps move around a little bit, each at their own rate
	- Rate is calculated once and maintained
	- Rate comprised of direction, length and speed of motion
	- The amount of variation has to be low, so it doesn't get completely insane
	

### Screen Gestures
- Tapping on screen generates a clone where the user tapped
- Double-tapping deletes clone
- Tapping and swiping moves clone around (not possible yet)

### Actor Motion
- Nothing