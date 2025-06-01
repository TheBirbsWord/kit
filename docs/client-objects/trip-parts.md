# Trip Parts

Trip parts are objects that will make the character enter the Sit state when touched by the player, making them enter a sitting animation and be affected by physics until a jump input is given.

Trip parts are defined as [`BaseParts`](https://create.roblox.com/docs/reference/engine/classes/BasePart) containing a `TripPartConfiguration`

## Use Cases
* Making complex tracks such as slides that will be able to move the player around in complex ways without worrying about default humanoid movement.
* Letting the player be interacted with as a physics object, such as letting the player bounce on parts with custom physical properties.

## Configuration

### `Cooldown`

The amount of time that needs to be passed before the player can activate the trip part again. `1` by default.
