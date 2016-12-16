# angrydrunks-changelog

This document will be continuously updated based on the changes during development. Since the App Store listing page limits the amount of text allowed, and since the updates need to specify exactly what's new... this document will list that out.

## 12/16/16
1. Esse projectile behavior
2. upgrade menus for mountain man and motorcyle mama have been added... they are not connected to the store yet. FYI - this is a work in progress, positioning and projectile behaivor are not 100%
3. removed audio error
4. swapped projectile icons for a projectile counter
5. reference the spreadsheet

---
## 12/06/16
1. added alternate dog with dog yelp sound on 31/32
2. resolved issue with bikeCop on jail level - this may happen with other rounds where an opponent is on screen but not included in the official hit targets. Fortunatly, it's an easy fix.
3. issue with the wooden nickel is resolved. again. for good this time... issue was with a wayward variable dealing with saving to file... not the algorithm.
4. round multiples of 5, earned beers are displayed again
5. intro vignette stops bg music and starts when done
6. bg music stops on round complete/fail continues during gameplay
7. odd bg shadow around throwing character removed
8. added support for upgrade characters - coming next update ;)

---
## 12/01/16
1. exit screen UI updated to match game... text is generic, TBD
2. scoring updates to prevent extra wooden nickels from appearing after making it interesting and winning
3. added walking do to round 31 as demo, will need to resolve proper placement
4. throwing sounds have been corrected
5. background music plays throughout... pause screen has mute. KNOWN ISSUE: background song will drop out after complete/fail screens - resolution to come in next update
6. projectile is now in front of objects
7. obstacles (garbage can, tires, cactus, construction barell) have been resized to be larger
8. resolve issue with jail scene clearing too soon
9. added wagon cop legs, also added additional fake targets to wagon jail (additional jails will be updated next update)
10. updated levels with cops in motion... jail scenes will have one staionary cop. Any of the moving riot cops can be updated to be a stationary or moving target
11. Menu screen Apha text has been changed to show build number... this is build 15

---
## 11/19/16
1. text on mii screen says "no wooden nickel" instead of ogre coin when none are present
2. scoring algorithm should correctly display beers/score/wooden nickels, 1 wooden nickel will be awarded after 24 beers are earned
3. KNOWN ISSUE: after purchasing a wooden nickel the score display on the make it interesting screen will not update. This issue is a communication error between the purchases controller and the display, only affecting this screen. The purchase will go through.
4. Main theme song loops (kinda) - switched to an Android only audio file, will need to resolve on iPhone when ready
5. Alert notice added for back button
6. throwing sounds updated for each character
7. fixed bounce issue again (hopefully)

*If it's not listed here, it's still a work in progress*

---
## 11/15/16
1. updated text on make it interesting screen
2. updated reload text on fail screen
3. updated buttons for mii
4. respositioned all characters on all rounds
5. increased difficulty on multiples of 5 rounds
6. found issue with marauder keg destroying jail
7. joe likes figs

---
## 10/31/16
1. repositioned ogre after swat truck destruction on esse levels
2. traffic light animation updated to remove light portion after destruction
3. enabled tgone speed up projectile
4. resolved issue of cops not clearing after large obstacles knocked down
5. added sound 'tap' for vignettes
6. added support for dual throwing characters (rounds 36+ are remain locked - levels are not fully set up yet)
7. updated main audio file to use a different format instead of mp3. the audio file properly loops in the simulator but wav files apprently are not compatible with android phones so the theme song will not play. need to find a new solution.

---
## 10/20/16
1. updated bouncing issue on car and some cop heads (issue may arise elsewhere, but the fix is now easy)
2. updated audio controls
3. resolved scaling of collisions with horseDeputy and motorcycleCop
4. resolved issue with smoke poof appearing in top corner
5. calculation and display of beers algorithm has been corrected
6. resolved some minor text/images/level adjustments
7. complete screen says "round" instead of "level"
8. resolved issue with hitting the tree on hippy's round
9. found some timing issues with large obstructions... some corrected, others remain work in progress

---
## 9/23/16
1. horse deputy and motorcycle cop collisions will behave as intended
2. resolved issues with audio/mute buttons
3. resolved issue causing runtime error when main character is throwing - issue was due to trying to repeat a throw while currently animating
4. resolved projectile size and visibility when level reloaded
5. resolved `nil index` runtime error when throwing character touched
6. resolved background parallax dragging issue when zoomed in
7. resolved issue of reappearing vehicle damage
8. resolved issue of disappearing projectile when hitting jail cells after removing hinges

####Known Issues
1. In-app purchases and earned coin algorithm are not functioning as intented. This issue is known and is being worked on.
