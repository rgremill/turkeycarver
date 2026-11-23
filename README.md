# Turkey Carver

A Thanksgiving game for the Atari 2600. The farmer on the ledge is throwing
carving knives at you, and you are the turkey. Dodge 16 rounds of knives to
earn a Turkey Pardon.

4K ROM, NTSC, one player, joystick.

## Files

- `turkey-carver.bin`: the ROM (4096 bytes). Load it in an emulator such as
  Stella, or on a flash cart such as the Harmony Encore.

## How to play

You are the turkey at the bottom of the screen. The farmer stands on the
ledge above and throws knives down at you. Move out of the way. Every knife
that falls past you without a hit is an escape and scores points. Clear all
of a round's throws to move on to the next round.

### Controls

| Control | What it does |
|---|---|
| Joystick left / right | Move the turkey |
| Fire button | Throw the knife you are carrying at the farmer (rounds 9+) |
| Joystick up | **Turkey Time**: slow motion, once per round |
| Select | On the title screen, pick the starting round (shown on the right of the HUD) |
| Fire (title screen) | Start the game |

In Stella, F1 is the console Select switch.

### Lives and score

- You start with 3 lives. A knife hit costs one life.
- Reaching certain score milestones earns a bonus life, up to a maximum of 3.
- Reaching round 16 refills you to 3 lives.
- Lose all your lives and you end up on the dinner plate. Press Fire to
  return to the title. Select only works there, so to restart at a later
  round, press Fire on the dinner screen, then Select (or push Up/Down) on
  the title, then Fire to start.

### The 16 rounds

| Rounds | Knives per throw | What changes |
|---|---|---|
| 1-4 | 1 | The farmer learns to lead your running and aim at your edges |
| 5-8 | 2 (pairs) | More throws per round, shorter gaps between them |
| 9-12 | 3 (trios) | The pickup knife appears |
| 13-16 | a random mix of 1, 2 and 3 | Wind pushes the knives sideways |

Knives always fall at the same speed. What gets harder is how many throws
come in a round, how quickly they follow each other and how well they are
aimed:

- **Lead throws** aim ahead of you, so hopping and stopping gets you hit.
- **Flank throws** clip the left and right edges of your turkey. Take a short
  step the wrong way and you walk into one.
- **Honing knives** bend toward you partway down.
- **Bursts** follow a throw with a second throw a moment later.
- **Wind** (rounds 13-16) drifts the knives sideways. The farmer's aim leans
  against it.
- **Angry sweep** (rounds 2, 3, 4, 6, 10 and 14): the farmer gets mad,
  stomps past you to the nearer edge of the field and lays down a rapid wall
  of knives that marches across the screen. Keep moving ahead of it and ride
  it out.

### The pickup knife (rounds 9 and up)

One white knife stands in the ground each round. Walk into it to pick it up,
then press Fire to throw it at the farmer. A hit stuns him, and he skips his
next two throws. Every knife already in the air is cleared and counts as an
escape. The farmer stands over you and flinches away if the knife is close,
so throw when he has settled above you.

### Turkey Time

Push the joystick up once per round to slow everything down. Save it for the
moment the screen fills up.

### Winning

Clear round 16 and the farmer gives in: you get the Turkey Pardon screen.
Press Fire to return to the title.

## Tips

- Look for the gaps, not just the knives. Pairs and trios leave lanes
  between the copies.
- Don't stand still. Every throw is aimed to threaten a turkey that stays put.
- In the wind rounds, judge a knife by where it will land, not where it starts.
- Round 16 is hard. Keep Turkey Time for it and take the pickup knife.

## Credits

Game and design by Robert Gremillion. Built with DASM.
