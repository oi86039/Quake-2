DOOM 2016 Gameplay Mod - Quake 2 Edition
- by Omar Ilyas

	Deliverable List (for easy grading)
		Complete:
		-- Modify Player movement + Double Jump
		-- Glory Kill System - increase gibs when attacking with melee
		-- Berserk Powerup
		-- Weapon Mod system
		-- Double Jump (Part of Modify Player Movement)
		
		Incomplete:
		-- Enemies Drop pickups on death

	How to make set up mod folder and create a Custom Steam Shortcut to test these deliverables:
	  *ONE TIME*
		- Copy the DOOM folder located in quake2-full-master/Project Folder
		- Paste the DOOM folder in the Quake 2 game directory (where the Quake2.exe is located)
		- Open the Steam Library
		- Navigate to Quake 2 in the sidebar on the left side of the Steam window.
		- Right-click on the title 'Quake 2' and select 'Properties'
		- In the options menu, select 'Set Launch Options'
		- Copy and paste the following line into the textbox that appears:
			+game DOOM +bind r firemode +bind mwheelup weapnext +bind mwheeldown weapprev +bind space jump
		- Click OK.
		
	  *On Game Restart*
		- Start a new single player game in Quake 2
		- Once in game, press the `~` key to open the console in-game. Type "give all" to grant all weapons and items to the player
		
	-All Completed Deliverables
		-- Modify Player Movement (including Double Jump)
			TO TEST:
				- Use WASD to move the character and spacebar to jump. You'll notice they move much faster than previously, although air movement is limited due to a bug.		
				- If the Berserk powerup is enabled, the player will move even faster for as long as the powerup lasts.
				- Double Jump is best tested by standing still and pressing the space bar. On the upper left, you'll see the word "JUMP" everytime you jump once, and "DOUBLE JUMP" if you jump while in mid air. Pressing the space bar multiple times will not increase the number of jumps.
		
		-- Increased Gibs
			TO TEST:
				- Kill a soldier or an infantry (heavy grunt) enemy with any weapon of choice. When an enemy is killed, they will explode into about 5 times as many gibs as they did previously.
				  *Be careful when killing multiple enemies at once, as Quake 2 cannot handle too many gibs at once without overflowing. Gibs disappear quickly to help aleviate the issue, but it can still arise since it takes about 4 seconds on average for gibs to disappear.
	
		-- Weapon Mod System (includes Melee)
			TO TEST:
				- Press the 'R' Key on your keyboard to switch weapon modes. On the upper left, you'll see the words "Mod INACTIVE" when the weapon uses default behavior and the words "MOD ACTIVE" when the weapon uses modded behavior.
				- Fire a weapon from the following list while in MOD ACTIVE mode to observe the altered effects.
				- All affected weapon behaviors are listed below:
					Melee (to access, press 1 with the blaster equipped)
						- Inactive: Punch with high damage and low knockback
						- Active: Punch with low damage, but high knockback (push)
					Blaster
						- Inactive: Fires a single blaster bolt
						- Active: Fires a single shotgun blast
					Shotgun
						- Inactive: Fire a single shotgun blast
						- Active: Fires a single rocket at reduced damage
					Super Shotgun
						- Inactive: Fire 2 shotgun blasts at increased damage
						- Active: Fire 5 shotgun blasts at increased damage
					Machinegun
						- Inactive: Fire bullets in fully-automatic mode one after the other
						- Active: Fire 3 shots in burst fire mode one burst at a time
					Chaingun
						- Inactive: Fire machinegun shots rapidly
						- Active: Fire contact grenades rapidly
					Grenade Launcher
						- Inactive - Fire a timed grenade that explodes after 2.5 seconds
						- Active - Fire a contact grenade that explodes in 0.75 seconds.
					Rocket Launcher
						- Inactive - Fire a single rocket
						- Active - Fire 5 rockets at a time
					Hyperblaster
						- Inactive - Fire blaster bolts rapidly
						- Active - Fire shotgun blasts rapidly
	
		-- Berserk Powerup (replaces Quad)
			TO TEST:
				- Press 'Q' on your keyboard to activate the Berserk Powerup.
				- While Berserk is active, all weapons EXCEPT for melee do 0 damage. The melee weapon, however, deals 10000 damage while berserk is active. Movement speed increases as well.
				- To switch to melee, press 1 on your keyboard while the blaster is equipped.

	-Incomplete Deliverables
		--Spawning Enemy pickups