# Blocks

## Events

```
on start {}
on timer([1sec|2sec|3sec|4sec|5sec|10sec|20sec|30sec|random]) {}
on buttonPressed([a|b|up|down|left|right]) {}
```
```
[knight|archer|pawn|goblin]<instance>:
on spawned {}
on collideWith([knight|archer|pawn|goblin|character|wall|anything])<other> {}
on near([knight|archer|pawn|goblin|character|wall|anything])<other> {}
on attackedBy([knight|archer|pawn|goblin|character|anything])<other> {}
on steppedOver([tile1|tile2]) {}
```

## Commands

```
win
lose
nextStage(stage)
resetStage
```
```
setVariable([score|lives|var1|var2|var3|var4|var5|var6}])To([0|1|2|3|4|5|6|7|8|9|10])
increaseVariable([score|lives|var1|var2|var3|var4|var5|var6])
decreaseVariable([score|lives|var1|var2|var3|var4|var5|var6])
```
```
repeat([1time|2times|3times|4times|5times|6times|7times|8times|9times|10times|forever|random]) {}
break
```
```
if buttonPressed([a|b|up|down|left|right]) {}
if numberOf([knight|archer|pawn|goblin])Is([0|1|2|3|4|5|6|7|8|9|10]) {}
if variable([score|lives|var1|var2|var3|var4|var5|var6])Is([0|1|2|3|4|5|6|7|8|9|10]) {}
if <instance>.steppedOver([tile1|tile2]) {}
if <instance>.near([knight|archer|pawn|goblin|character|wall|anything]) {}
```
```
spawn([knight|archer|pawn|goblin])Near(<instance>)
spawn([knight|archer|pawn|goblin])Near([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
```
```
wait([1sec|2sec|3sec|4sec|5sec|10sec|20sec|30sec|random])
```
```
<instance>.move([up|down|left|right|random])
<instance>.moveAwayFrom(<instance>)
<instance>.moveAwayFrom([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
<instance>.moveTowards(<instance>)
<instance>.moveTowards([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
<instance>.attack
<instance>.shoot(<instance>)
<instance>.shoot([up|down|left|right|random])
<instance>.destroy
```

## Instances

```
random([knight|archer|pawn|goblin|character|wall|anything])
first([knight|archer|pawn|goblin|character])
last([knight|archer|pawn|goblin|character])
next([knight|archer|pawn|goblin|character])After(<instance>
previous([knight|archer|pawn|goblin|character])After(<instance>)
closest([knight|archer|pawn|goblin|character])To(<instance>)
closest([knight|archer|pawn|goblin|character])To([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
furthest([knight|archer|pawn|goblin|character])From(<instance>)
furthest([knight|archer|pawn|goblin|character])From([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
```

# Mini Games

## Space Invaders

```
level has goblins in one row on top from left to right and an archer on the bottom
bottom area tiles are ground with village
archer can move right and left with buttons and attack on button up
golbins on spawn in loop move left left left bottom right right right bottom
goblin on attacked is destroyed
if number of goblin is 0 win
if goblin collided with archer lose
if golbin stepped over ground lose
```

## Arkanoid

```
level has goblins as bricks
ship acts as the ball and knight as the paddle
two variables store sheep direction x and y
sheep moves up down left right according to variables x and y
sheep on attached by knight variable y changes
sheep on stepped over boundary variable x changes
if ship collides with goblin destroy the goblin and change y
```

## Soccer

## Pacman

## Golf
