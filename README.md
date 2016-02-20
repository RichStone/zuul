# zuul

A small zuul clone built in [Läsp](https://github.com/alcesleo/lasp).

## Example

```
$ lasp zuul.lasp
You are in the entrance hall.
Exits: west, east

What do you want to do? west
Invalid action.
You are in the entrance hall.
Exits: west, east

What do you want to do? go west
You are in the west wing.
Exits: east

What do you want to do? go west
Invalid direction
You are in the west wing.
Exits: east

What do you want to do? go east
You are in the entrance hall.
Exits: west, east

What do you want to do? go east
You are in the east wing.
Exits: west

What do you want to do? quit
Bye!
```
