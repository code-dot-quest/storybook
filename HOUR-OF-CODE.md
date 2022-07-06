# Hour of Code

Purpose: In one hour, take a person without any knowledge and show them the basics.

## Video - Getting started

Explain about the screen layout, show how to add a command and how to run the code.

## Level 1 - Basics - Add one command

Story: TBD

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

Story: Maybe take some item and introduce inventory.

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

Story: Many repeated actions and a slash at the end.

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
  knight.slash
}
```

## Video - Loops

Explain about loops and how they save us from extra work.

## Level 4 - Loops - Loops in action

Story: TBD

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
