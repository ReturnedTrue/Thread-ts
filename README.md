# Thread-ts
Roblox-ts typings for Thread.lua, a gist made by CloneTrooper1019.

# Installation
```
$ npm i --save-dev @rbxts/thread
```

# Usage
```ts
import Thread from '@rbxts/thread';

let [delay, elapsed] = Thread.Wait(2); // waits for 2 seconds

Thread.Spawn((one, two three) => {
    // Spawned in a separate thread
}, 1, 2, 3)

Thread.Delay(2, (delay, elasped) => {
    // Ran after 2 seconds in a separate thread
})
```