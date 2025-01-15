# Updated opvar fgd and zoo map
Updated opvar fgd &amp; zoo map for arrays

![hlvr_01-14_DOvM0](https://github.com/user-attachments/assets/1c184af6-a0ed-4f80-8302-967846577559)
## Installation
Backup and replace `base.fgd` located in the `game/core/` directory of Half-Life Alyx. 
## FGD Changes
### Better grouping!
In base HLA all the opvar settings are lumped together, this makes it pretty difficult to wrap your head around different parts of the system. The new FGD modifies this so everything is separated by Sound Stack, Distance, Occlusion, and Disable Behavior.
### Dropdowns!
Instead of memorizing the names of all the common array types in HLA, I added a dropdown that shows them all instead! Skylight Proximity and Small Room are the ones you'll use most in the audio workflow, so those are at the top. Arrays that invert these values are right below them too.
### Better defaults!
The defaults are pretty bare in base HLA, I updated these so they're more sensible for what you'll be doing most. No more adding boilerplate stack scopes!
### More documentation!
The lack of documentation is the worst part of the opvar system, you'll be spending a lot of time looking at the base HLA vmaps to see how Valve implemented them. I added and clarified tool hints in the fgd so it should be a bit easier to get a foothold.


