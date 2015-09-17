# CraftMine
The future of CraftMine starts now.

## Build number convention
Each potentially game-breaking change goes in a new build, so that if the game breaks because of a change, you can revert your changes without also reverting all your previous changes also included in that build.

Example
-------
Current build is 0005, but I want to add a new mod called "Buildcraft". Before adding it, I clone the current build and name it b0006, then add my new mod. When testing, if the new mod is too buggy or laggy or it crashes the game or whatever, I delete build 0006 and go back to using b0005. This way, I don't loose any of the other changes I made in b0005 before I added the new mod. If the mod added in works perfectly, I configure it and then leave it in the new build and carry on with adding new stuff and changing things, etc...

## When not to make a new build
- After a minor change (for example, tweaked a couple of configs which doesn't do much)
- After a new texture, audio or resource addition (these should be made in a new version of the resourcepack or whatever and done seperately from CM - not done inside CM)

## Submitting a patch
Submit a pull request containing your new changelog, configs and mod names. Once your pull request has been reviewed, it will be attempted as a patch in CM and if it passes, your pull request will be approved. Once your patch has been approved, you may continue developing a new build.

## Submitting a texture change
Use skype for this
