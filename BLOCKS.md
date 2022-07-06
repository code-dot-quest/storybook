# Events

```
on start {}
on timer([1sec|2sec|3sec|4sec|5sec|10sec|20sec|30sec|random]) {}
on buttonPressed([a|b|up|down|left|right]) {}
```
```
knight<instance>
on spawned {}
on collideWith([knight|archer|pawn|goblin|character|wall|anything])<other> {}
on near([knight|archer|pawn|goblin|character|wall|anything])<other> {}
on attackedBy([knight|archer|pawn|goblin|character|anything])<other> {}
on steppedOver([tile1|tile2]) {}
```

# Commands

```
win
lose
nextStage(stage)
resetStage
```
```
repeat([1time|2times|3times|4times|5times|6times|7times|8times|9times|10times|forever|random]) {}
```
```
if buttonPressed([a|b|up|down|left|right]) {}
if numberOf([knight|archer|pawn|goblin])Is([0|1|2|3|4|5|6|7|8|9|10]) {}
```
```
spawn([knight|archer|pawn|goblin])Near(<object>)
spawn([knight|archer|pawn|goblin])Near([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
```
```
wait([1sec|2sec|3sec|4sec|5sec|10sec|20sec|30sec|random])
```
```
<instance>.move([up|down|left|right|random])
<instance>.moveAwayFrom(<object>)
<instance>.moveAwayFrom([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
<instance>.moveTowards(<object>)
<instance>.moveTowards([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
<instance>.attack([forwards|backwards|up|down|left|right|random])
<instance>.destroy
```

# Instances

```
random([knight|archer|pawn|goblin|character|wall|anything])
first([knight|archer|pawn|goblin|character])
last([knight|archer|pawn|goblin|character])
closest([knight|archer|pawn|goblin|character])To(<object>)
closest([knight|archer|pawn|goblin|character])To([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
furthest([knight|archer|pawn|goblin|character])From(<object>)
furthest([knight|archer|pawn|goblin|character])From([topLeft|topCenter|topRight|centerLeft|center|centerRight|bottomLeft|bottomCenter|bottomRight])
```
