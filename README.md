# Source SDK Test Maps
Made using hammer.

Just some maps helping me to learn hammer.

<br>

# Useful guides
* [Soundscapes](/soundscapes.md)
* [Custom materials](/custom-materials.md)
* [Hammer/Source SDK mapping tutorials](https://www.youtube.com/playlist?list=PLfwtcDG7LpxF7-uH_P9La76dgCMC_lfk3)
* [TopHATTWaffle mapping tutorials](https://www.tophattwaffle.com/tutorials/)
* [Setting up maps for NCPs](https://www.youtube.com/watch?v=r3jgAIsbySg) (nodegraph & info nodes)
    * Used by NPCs
* [Setting up maps for bots](https://www.youtube.com/watch?v=hShf-Kl7EHY) (navmesh)
    * Used by nextbots- https://developer.valvesoftware.com/wiki/NextBot
    * You might need to do this first
        * Open the map
        * Point your crosshair at a walkable surface
        * Type nav_mark_walkable
        * Then run nav_generate (this may take some time and freeze your game until it's done)


<br>

# Map Names
* First maps
    * [First](#first) - [map files](/maps/first-maps/001-first/)
    * [Second](#second) - [map files](/maps/first-maps/002-second/)
    * [Third](#third) - [map files](/maps/first-maps/003-third/)
* Basic maps
    * [Lighting](#lighting) - [map files](/maps/basics/lighting/)
    * Light beams - [map files](/maps/basics/light-beams/)
    * Water - [map files](/maps/basics/water/)
        * Lots of different water textures
        * The water in this map won't render properly, due to there being a mixture of different water types
    * 3D Skybox test - [map files](/maps/basics/skybox/)
    * Optimisation - [map files](/maps/basics/optimisation/)
        * Area portals
        * How the skybox hides parts of your map
        * How visleafs split up the map
    * Soundscapes [map files](/maps/basics/soundscapes/)
        * Tests some indoor and outdoor soundscapes
        * Tests transitioning between soundscapes
        * Ingame, enter the following console commands to see what's happening
            * `developer 1`
            * `soundscape_debug 1`
* Entity test maps
    * Some basic map logic - [map files](/maps/entities/logic/)
        * Using buttons, triggers, lights
    * Non-breakable props - [map files](/maps/entities/nonbreakable-props/)
    * Double doors - [map files](/maps/entities/double-doors/)
    * Moving Cars - [map files](/maps/entities/moving-cars/)
    * Trapdoor - [map files](/maps/entities/trapdoor/)
        * A basic trapdoor
        * A trapdoor which only works for ragdolls
    * Ropes & hanging things from ropes - [map files](/maps/entities/rope/)
* Other maps
    * Fothergill window style - [map files](/maps/test/styles/)
    * [Halloween map features](#halloween) - [map files](/maps/test/halloween/)



# Map Details


## First
[Map files](/maps/first-maps/001-first/)<br>
* Skybox
* Limited intended playable area
* Cubes
![Some blocks](/Screenshots/first.jpg)

## Second
[Map files](/maps/first-maps/002-second/)<br>
* Skybox
* Basic level design
* Props
* Water
* Sunlight
* Light sources
* Non-cube shapes
* Fog
![Water, lamps, props and walls](/Screenshots/second.jpg)

## Third
[Map files](/maps/first-maps/003-third/)<br>
* An actual map
* Enterable buildings
* Evening lighting
* Basic, multi-level terrain
* Doors
* Decoration props
* Improved interations with details objects (e.g. door frames, stair railings)
* Alternative paths through map
![Two houses](/Screenshots/third.jpg)
![Alleyway](/Screenshots/third-2.jpg)<br>
[Map files](/maps/first-maps/003-third/)<br>

<br><br><br><br>


## Lighting
[Map files](/maps/basics/lighting/)<br>
![lighting](/Screenshots/lighting.jpg)<br>



<br><br><br><br>


## Halloween
[Map files](/maps/test/halloween/)<br>
Tests a load of halloween map features

* Skull objective- collect skulls to unlock secrets
    * Skulls- https://steamcommunity.com/sharedfiles/filedetails/?id=548759509
    * Zombies spawn
    * Fog
    * Low gravity
    * Healing station
* Dark sky, lighting, fog
    * Skybox Grimm night- https://gamebanana.com/textures/1776
* A basic jump scare

![Halloween](/Screenshots/halloween.jpg)<br>
[Map files](/maps/test/halloween/)<br>
