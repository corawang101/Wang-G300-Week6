# Wang-G300-Week6

## Colors and Point Values
Yellow Box: Destroyed by hitting them from below. Awards 1 point when destroyed
Blue Box: Destroyed by jumping on them from above. Awards 1 point when destroyed
Launch Pad: Red, np points
DoorToDestrot: White
Purple PowerUpBall: The powerup ball appears after the player destroy all boxes.

## Further Points
### Cohesive Level Design
I designed the level so that the player must complete the obstacles in
a specific progression instead of simply running directly to the end.

The powerup ball is initially hidden and cannot be collected. The player
must destroy all of the required yellow and blue boxes first. Destroying
the boxes increases the player's score, and when the score reaches 6,
the powerup ball appears.

The next platform is intentionally too high for the player to reach
normally. This makes collecting the powerup necessary for progression.
After collecting the powerup, the player's jump height is temporarily
increased, allowing the player to reach the higher platform and continue
through the obstacle course.

### Jump Powerup
When the player collects the powerup, their jump velocity is temporarily
increased. This allows the player to reach a platform that cannot be
reached with the normal jump. After several seconds, the player's jump
velocity returns to its normal value.
