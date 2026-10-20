# in-class-activities
## Devlogs
### W1
Activity 1
1. When the camera is removed from being a child of the cat, the camera stays while the cat moves around since they're not longer bound and inheriting movement.
2. Link to itch page: https://deeel.itch.io/my-first-steps


### W2
Activity 2
1. The r, g, and b values are floats rather than any other data type because they're not something that can be either true or false,
strings are primarily letters and they can't work with the mathematical operations done in the code easily, and while I think
technically an int COULD be used, I think Unity just prefers it, probably for some kind of hardware thing.
2. The _bounce variable is an integer rather than any of the other data types because bounces only happen in increments of one,
there can't be half a bounce, it isn't a true or false question, and bounces are tracked by numbers rather than words. Therefore,
it makes the most sense to use an integer.
3. The error was that the code was missing an f since the compiler was particularly getting upset about what was going on with regards
to the number not including it for the type of variable in play.

### W3
Activity 3 (Table #4)
1. For the visual novel, in the header we should probably have a boolean in place for the flag to check whether the relatio
2. nship is high enough or not,
a string to contain the response, and have that string be returned for GetResponse.
3. Since the horror game doesn't need any output, we can have a void method with a float or int parameter for the sanity level. We do not have a return.
4. For the DidPlayerHitBeat, we should have a boolean and a float parameter that lets the game know if they hit the note or not and returns the press time float. 
5. We compared the relationships between classes and components to tacos. We said that a class is like the tortilla that suits whatever you're trying to make,
whether it be a soft shell, hard shell, or etc., whereas the this tortilla becomes a component through added ingredients and whatnot. You can also have combos of tacos like in a luxe box.
6. I think because it's a multiplier, it will eventually go exponential given enough time and bounces which will get insanely bright.

### W4
Activity 1
1. We said that the cat and ball both need rigid bodies since they need to move in the environment and interact while the goal needs a trigger since it's static.
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
