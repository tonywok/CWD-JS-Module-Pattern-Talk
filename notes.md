## Anonymous Closures

- all vars and functions are only in this scope.
- has access to all globals

## Passing in Globals

- When using a global, javascript walks the scope change backwards looking for var statements.
- If it isn't found, it is global. If it does not exist, it is created.
- Passing in globals to our anonymous function prevents this lookup (faster).
- Ability to rename within the closure to avoid name conflicts

## Augmenting across files

- Able to be loaded asynchronously even though they are shared across files because of memoization.
- This allows libraries like Lab.js and Require.js to do their thing.

## Submodules

- Offer a namspace, work just like regular modules

## Public API Variation, Function Injection

- Wing it.
