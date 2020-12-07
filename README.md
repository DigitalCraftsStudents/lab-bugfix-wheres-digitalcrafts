# Where's DigitalCrafts?

This program displays the states which have cities named "Atlanta", "Houston", "Tampa".

# Bugs to fix

- [X] After lots of debugging, code stopped running. `node index.js` does nothing
  - `main()` needed to be uncommented in `index.js`
- [X] Started crashing after adding "tampa" search
  - `statesWithCity('tampa')` needed a `db.` prefix
- [X] Prints "Atlanta" locations twice (instead of Houston)
  - Changed loop to use `statesWithAHouston` on line 15.

For each bug you fix, add documentation to this README about how you fixed it (include before/after code samples).

# For the more curious:

`db.js` includes more functions that you can try out. In `index.js`, try to `console.log()` the results of the following function calls:

- `getByAbbreviation('ak')`
- `searchByName('dakota')`
  - Why does this only return results for North Dakota (and not South Dakota)?
