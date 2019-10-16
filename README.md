# design-system
repo for prototyping new componentized design system

## Grid system and box model

padding and margins are in multiples of 8px. So 8px is the foundation of our measurement system in the box model. Instead of expressing this in px, we can use multiples of x.

8px = 1x  
16px = 2x  
...  
40px = 5x  
...  

since we use less and its variable naming system uses `@` as a prefix, in practice, these variables look like this:

```
@1x: '8px';
@2x: '16px';
...
@5x: '40px';
```

#### NOTE: do not confuse this with iOS @1x, @2x nomenclature for their stupid pixel density design crap. iOS is bad and they should feel bad.
