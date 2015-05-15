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