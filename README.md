# Color Catch VR

Color Catch VR is a simple reaction and color-recognition game built in Unity for Windows PC and PC VR.

Players must catch only the balls that match the target color shown on screen while avoiding the wrong colors. The game becomes harder across 10 levels with faster spawns, higher falling speed, and larger score goals.

## Game Overview

- Catch the ball only if it matches the target color.
- Correct catch: `+1`
- Wrong catch: `-1`
- Ball touching the ground: no score
- Complete the level before time runs out
- Finish all 10 levels to win the game

## Download And Play

To play the game, download `Color Catch XR Share Build.zip` from this repository and extract it.

Important:
- Keep all build files together in the same folder
- Do not move only the `.exe` file by itself

Run:
- `Color Catch XR.exe`

## Files Needed

The playable Windows build includes:

- `Color Catch XR.exe`
- `Color Catch XR_Data`
- `MonoBleedingEdge`
- `UnityPlayer.dll`
- `UnityCrashHandler64.exe`
- `dstorage.dll`
- `dstoragecore.dll`
- `D3D12`

This repository already includes:

- `Color Catch XR Share Build.zip`

That zip contains the full playable Windows build.

## Controls

### PC Keyboard Mode

- `Enter` = Start game / next level
- `W A S D` = Move left hand
- `Arrow Keys` = Move right hand
- `Esc` = Pause menu
- `R` = Restart game

### VR Mode On PC

Connect a VR headset to the PC and make sure the OpenXR runtime is active.

Then run:

- `Color Catch XR.exe`

The game can be played in VR using the same Windows build.

## How To Play

1. Start the game.
2. Look at the target color shown on screen.
3. Catch only balls with the matching color.
4. Avoid wrong-colored balls.
5. Reach the level goal before the timer ends.
6. Press `Enter` to go to the next level after winning.

## Level Progression

The game contains 10 levels with increasing difficulty.

- Level 1 is a warm-up
- Levels 2 to 4 are normal difficulty
- Levels 5 to 7 are challenging
- Levels 8 to 10 are hard final levels

## Built With

- Unity
- C#
- OpenXR

## Note

This GitHub upload is for the playable Windows PC / VR build.
Unity source files are not required for players who only want to download and play the game.
