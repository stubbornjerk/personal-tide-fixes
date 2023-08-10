# disclaimers
  Based on ElectricAlice's Ao3-tide. ElectricAlice's Ao3-tide (with subsequent fixes) can be found here: https://github.com/electricalice/Ao3-tide/tree/main
<br>Their tutorial can be found here: https://archiveofourown.org/works/32660914

# previews
if you're curious what the skins look like, here: 
    <br>purple-light
    <br>https://imgur.com/a/bQd6Vfr
<br><br>
    <br>blue-dark
    <br>https://imgur.com/a/NakwFT4

# remarks
  I didn't alter much, I just changed the colorway and figured I'd put my version of the codes + tutorials here. If you want to assemble it yourself, follow their tutorial, it's actually pretty straightforward. I guess my takeaway is that they never really specify what they mean by "unique" across the site because I don't speak code.
  <br>I made specifications so it activates the skin based on if you have dark mode on your browser or not. I'm trying to improve my eye health so... I'll put that in a separate thing.

# unique titles
  What they really mean about that is that it's like a username. Ao3 doesn't tell you that if you use a common name for a site skin, people can accidentally yoink it from your list of site skins even if they can't edit or alter it.
  <br>So, make sure you're going to name it something like "[username] tide dark" or "[username] tide phone" because otherwise you're going to yoink someone else's code and chances are they did not use the same colorways as you. Just bear that in mind.

# colorway changes
  If you're going to change the colorways on the light mode version, here's the colors you have to ctrl+f and replace yourself.
<br>ElectricAlice's colors > My colors
  <br>d84549 > 9645d8
  <br>bd302a > a320bd
  <br>e0878a > a887e0
  <br>d1e9eb > de91eb
  <br>eed8d9 > d9d8ee
  <br>f0e6e6 > e6e6f0
  <br>e14c74 > 7c44e1
<br>I put my colors there in case you grabbed my purple light version.

# font changes
 If you're going to change the main work font, focus on this part of the code for both light and dark mode:

<br>body,
<br>input,
<br>.toggled form,
<br>.dynamic form,
<br>.secondary,
<br>.dropdown,
<br>button,
<br>blockquote,
<br>.filters dt,
<br>.filters dd,
<br>.filters input[type=submit],
<br>.filters .expander,
<br>.bookmark .user .meta,
<br>.datetime,
<br>a.work,
<br>span.symbol,
<br>.splash .news .meta,
<br>select {
  <br>font-family: Avenir, Helvetica, Arial, sans-serif;
<br>}
<br><br>
<br>Change that last part to whatever type face you want. This is just to change the font you're going to be reading most works in + tags, etc. It won't affect work titles.
