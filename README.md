# Super Quest – The Lost Kingdom

A 2D side-scrolling platformer that runs in your browser. All art and sound are generated in code with HTML5 Canvas and the Web Audio API, so there are no image or audio files.

## How to run
1. Open `super-quest.html` in a modern desktop browser (Chrome, Edge, Firefox or Safari).
2. Click anywhere or press a key once so the browser allows sound.
3. No installation or server is needed. It also works when hosted as a web page.

## Controls
| Action | Keys |
|---|---|
| Move | A / D or Left / Right arrows |
| Jump | Space, W or Up arrow (press again in the air to double jump; hold for a higher jump) |
| Sprint | Shift |
| Crouch / slide | S or Down arrow (slide while sprinting) |
| Time slow | E (about 12 second cooldown) |
| Fireball | F or J (needs the Fire power-up) |
| Pause | Esc |

A gamepad also works: left stick to move, A to jump, X to shoot, Y for time slow, B or the right bumper to sprint.

## Gameplay
- Reach the flag at the end of each level.
- Stomp enemies by landing on them, or burn them with fireballs.
- Boss levels (the third level of each world) keep the flag locked until you defeat the boss.
- Collect coins for score and stars.
- Touch checkpoint flags to respawn there after dying.
- You have 5 lives per attempt. When they run out, you retry the level.

### Power-ups
| Power-up | Effect |
|---|---|
| Fire | Shoot fireballs |
| Speed | Run faster |
| Shield | Absorbs one hit |
| Magnet | Pulls in nearby coins |
| Glide | Hold jump to slowly descend |

### Stars
Each level gives up to three stars:
1. Finish the level.
2. Collect at least 70% of the coins.
3. Finish without taking damage.

## Worlds
1. Green Valley (boss: Slime King)
2. Desert Kingdom (boss: Sand Pharaoh), with wind
3. Frozen Peaks (boss: Frost Golem), with slippery ice
4. Mystic Forest (boss: Elder Treant), a dark, foggy night
5. Lava Fortress (boss: Magma Drake)
6. Sky Kingdom (boss: Storm King), with strong gusts

Each world has 3 levels. Levels unlock in order, and you can replay any unlocked level from Level Select.

## Settings
Music volume, sound effects volume, difficulty, screen shake and fullscreen.

| Difficulty | Health | Enemies | Boss health |
|---|---|---|---|
| Easy | 5 hearts | Slower | 6 hits |
| Normal | 3 hearts | Normal speed | 8 hits |
| Hard | 2 hearts | Faster | 10 hits |

## Saving
Progress, stars, coins, achievements and settings are saved automatically in your browser's LocalStorage. Use **New Game** in the main menu to reset progress. Clearing your browser data also erases the save.

## Known limitations
- Controls cannot be remapped.
- Not built: ladders, slopes, moving platforms, water sections, portals, secret levels, daily challenges, character skins and the local leaderboard.
- All six bosses share the same attack logic.
- Levels are generated from a fixed seed, so each level is the same on every play.
