# Magic 8-Ball

A JavaScript Magic 8-Ball script. It greets a user, uses the question “Will I adopt a new puppy soon?”, picks a random integer from 0 to 7, and maps some of those values to replies such as “It is certain.” and “My sources say no.”

Not every number in that range has a `switch` case in the current file, so some runs will print an empty answer. Several `console.log` strings also use single-quoted templates with `${...}`, which JavaScript will not interpolate.

## Getting started

```bash
node main.js
```

Practices: `switch`, randomness, and conditionals.
