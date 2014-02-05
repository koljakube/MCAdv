# The Sewers

## Sewer Pieces

### Straights

Towards positive Z: spawns left and ahead of you
Towards negative Z, spawns right and behind you
/clone -575 74 387 -569 82 382 ~ ~ ~ replace

Towards positive X: spawns right and ahead of you
Towards negative X: spawnt left and behind you
/clone -577 76 415 -583 83 421 ~ ~ ~ replace

### Bends

Negative X to positive Z
Position: Outermost corner
/clone -563 73 397 -570 81 404 ~ ~ ~ replace

Positive X to positive Z
Position: Most negative X and Z
/clone -596 77 417 -589 84 410 ~ ~ ~ replace

Positve Z to negative X
Position: Innermost corner
/clone -578 74 394 -585 82 401 ~ ~ ~ replace

### Stairs

Towards negative Z: Clone at bottom left
/clone -568 93 366 -574 83 355 ~ ~ ~ replace

Towards positive X: Clone at top left
/clone -581 77 363 -592 88 369 ~ ~ ~ replace

Towards positive Z: Clone at top right
/clone -546 106 402 -552 94 418 ~ ~ ~ replace

Towards negative X: Clone at bottom right
/clone -582 84 431 -568 96 425 ~ ~ ~ replace

## Sewer Monster Spawning

General Scoreboard Commands:

    /scoreboard players set @a mspSewersXXXX 0
    /scoreboard players set @a mspSewersXXXX 1

## mspSewersXXXX

### Test for Player at Location

    /testfor @p[x=-610,y=80,z=285,r=10,score_debugNoSpawn=0,score_mspSewersXXXX=0]

### Comparator (De-)Spawning

    /setblock -596 47 280 unpowered_comparator 3
    /setblock -596 47 280 air
    
### Monsters:

1. `/summon Slime -576 77 296 {Size:1}`
2. `/summon Slime -576 77 296 {Size:2}`
3. `/summon Slime -576 77 296 {Size:1}`
4. `/summon Slime -576 77 296 {Size:2}`
5. `/summon Slime -576 77 296 {Size:3}`

### Debug Output

    /testfor @p[x=-610,y=80,z=285,r=10,score_debugDoOutput=1]
    /say mspSewersXXXX
    
    
    
    
/summon unpowered_comparator -592 76 295 4
/setblock -592 76 295 unpowered_comparator 3
/setblock -592 76 295 air


