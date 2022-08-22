# screeps-arena-optimization

Screeps Arena requires significantly less optimization than Screeps World for the following reasons:
* You get 50 ms per tick, as opposed to the 20 ms most people get per tick in Screeps World.
* You get 1000 ms on the first tick, which can be used for essentially any amount of initialization.
* There's only one room, which is the same every time, instead of a big map full of a variety of rooms.
* Everything in `global` persists between ticks, so there is no JSON overhead.
