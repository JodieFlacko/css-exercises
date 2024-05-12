# Accidentally erased the whole commits history with ` git restore ` command.

I used ` git restore <first commit> ` . Then had issues trying to push, raised error for misplaced HEAD. ` git push -f ` after that probably screwed everything. Now I'm left without snapshots of my older versions and don't recall the various changes I made, but i learned a lesson: be careful with ` git reset `.