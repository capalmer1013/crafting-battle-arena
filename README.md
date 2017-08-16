# crafting-battle-arena
Time to play with Game Maker and make essentially rust. but top down 2d style

## Procedurally generate map

characters are 32x32 square

8x8 biomes (64 biomes in global map)

Each Biome is 512x512 squares(square is 32x32 px)

outside biomes wasteland

- Biomes: Large square sections of map
    - Wasteland: 
        - very limited resources
        - really good items
        - many aggressive NPCs

    - Forest:
        - limited items
        - high trees
        - moderate rocks 
        - few aggressive NPCs

    - Mountains:
        - moderate items
        - more aggressive NPCs
        - many rocks
        - moderate trees

    - Water:
        - all surrounding areas have land
        - some boats
        - scattered islands in the middle
        - needs something else
    
- Structures:
    - walls
        - wood
        - stone
    
    - bridge:
        - wood
        - stone

    - trees
    - boulders
    
- Items:
    - rock
    - wood
    - spear
    - bow
    - arrow
    - 

- BaseCharacter Attributes:
    - name
    - health
    - healthMax
    - items
    - fatigue
    - motivation

- NPCs inheirits from BaseCharacter
    - aggression
    - state
    - stateMachine(required states, there can be more)
        - move
        - attack
        - hunt
        - eat
        - build
        - mine
        - idle

- Player inheirits from BaseCharacter

## Milestones:
- generate single biome ( no characters )
- add player character to biome
- add NPCs to biome
- add global map with multiple biomes
- add multiplayer to biome
- possibly add doom style 3d option (not real 3d but 3d represented in 2d)
