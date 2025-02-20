# Packages
Packages for Monster Train 2 to make modding easier

## What is this?

To make modding easier and not hard-path coded we collect the public code APIs into a package. This is standard practice for all games included for BepInEx.

These Packages do not contain the game, nor any ability to run the game... all it contains is code for the 

## How to Build:

These cannot be build automatically, they must be done manually.

Provided in the Repo is a .nuspec file, when a new version of the game is released go ahead and do the following:
1. Go to steam and copy the Build ID in properties for the game.
2. Go to Local files and copy the provided .nuspec
3. Update the nuspec version to be the build ID, also increment the minor version. If it is a major content version, increment the major version.
4. run `nuget pack .nuspec`
5. Upload the built package
