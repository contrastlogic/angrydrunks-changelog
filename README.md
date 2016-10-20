# angrydrunks-changelog

This document will be continuously updated based on the changes during development. Since the App Store listing page limits the amount of text allowed, and since the updates need to specify exactly what's new... this document will list that out.

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
