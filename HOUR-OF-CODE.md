# Hour of Code

Purpose: In one hour, take a person without any knowledge and show them the basics.

## Levels

1. Basics - Add one command
2. Basics - Add multiple commands
3. Loops - Why we need loops
4. Loops - Simple loop
5. Loops - Complex loop
6. Conditionals - Simple conditional
7. Conditionals - Complex conditional
8. Functions - Why we need functions
9. Functions - Simple function
10. Functions - Two functions
11. Events - Simple event
12. Events - Multiple events
13. Free play

## Video - Getting started

Explain about the screen layout, show how to add a command and how to run the code.

## Level 1 - Basics - Add one command

Story: TBD. Knight just needs to move 2 steps for some reason.

Blocks:
```
knight.move(up|down|left|right)
playSound(grunt)
```
Workspace:
```
on start {
  knight.move(right)
}
```
Solution:
```
on start {
  knight.move(right)
  knight.move(right)
}
```
 
## Level 2 - Basics - Add multiple commands

Story: TBD. Knight moves again, just a little more complex path. Maybe take some item and introduce inventory.

Blocks:
```
knight.move(up|down|left|right)
playSound(grunt)
```
Workspace:
```
on start {
}
```
Solution:
```
on start {
  knight.move(down)
  knight.move(right)
  knight.move(right)
}
```

## Level 3 - Loops - Why we need loops

Story: TBD. Knight needs to travel further and hit something? Many repeated actions and a slash at the end.

Blocks:
```
knight.move(up|down|left|right)
knight.slash
playSound(grunt)
```
Workspace:
```
on start {
}
```
Solution:
```
on start {
  knight.move(up)
  knight.move(up)
  knight.move(up)
  knight.move(up)
  knight.move(up)
  knight.move(up)
  knight.move(up)
  knight.slash
}
```

## Video - Loops

Explain about loops and how they save us from extra work.

## Level 4 - Loops - Simple loop

Story: TBD. Knight is doing a repeated action.

Blocks:
```
knight.move(up|down|left|right)
knight.slash
playSound(grunt)
repeat(1 time|2 times|3 times|4 times|5 times|6 times|7 times|8 times|9 times |10 times|forever) {}
```
Workspace:
```
on start {
  repeat(5 times) {
  }
}
```
Solution:
```
on start {
  repeat(5 times) {
    knight.move(right)
    knight.move(down)
  }
}
```
```
on start {
  repeat(5 times) {
    knight.move(right)
  }
  repeat(5 times) {
    knight.move(down)
  }
}
```
Extra: Can you solve this with one repeat statement instead of two.

## Level 5 - Loops - Complex loop

## Video - Conditionals

## Level 6 - Conditionals - Simple conditional

## Level 7 - Conditionals - Complex conditional

## Level 8 - Functions - Why we need functions

## Video - Functions

## Level 9 - Functions - Simple function

## Level 10 - Functions - Two functions

## Video - Events

## Level 11 - Events - Simple event

## Level 12 - Events - Multiple events

## Video - Summary

## Level 13 - Free play
