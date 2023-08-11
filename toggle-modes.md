# Tutorial
This is **only applicable if you've done all of ElectricAlice's steps** up until the phone/mobile fix. By this point, **you should have three (3) site skins,** 
and you **should only be using your phone fix skin.** If you only use the regular ones even in light mode, it will look wonky on mobile.

Now. Here's how this should go.

1. Create another skin for the only other skin you don't have. If you made the light mode your base, this should be the dark mode. Vice versa.
2. Paste the CSS code for that corresponding version.
3. Under @media, scroll down to (prefers-color-scheme:light) or (prefers-color-scheme:dark). If the code you added is your light mode version, pick light. dark for dark mode
4. Go to your parent skin (your base light or dark mode). Under @media, toggle the appropriate prefers-color-scheme box. Update.
5. Finally, go to your phone fix skin again and add the new skin as a parent skin.

and you're done!

in total, **you will have four (4) site skins. You should still only be using your phone fix skin.**

# important
Again, you should make sure that the titles are "unique". I ran into some trouble when Ao3 kept auto-choosing other people's versions of this site skin. 
So make sure your site skin title is personalized in some way, otherwise, it's going to look ugly.

If your browser is in either mode, the site skin will toggle automatically. same if your browser is following the system mode you're using.

If you have Dark Reader (the extension) on, the dark mode site skin will toggle ***only*** if you have the extension on Light. To switch to the light skin,
****turn the extension off.****
