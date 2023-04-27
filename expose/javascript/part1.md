1. Line 9 will return 20.
2. Line 13 will also return 20.
3. Line 9 will return 20.
4. Line 13 will throw an error because `result` is now out of scope.
5. Line 9 will throw an error becuase `result` was defined as a `const` and line 7 attempts redefine `result` which is an error.
6. Line 13 will return an error becuase `result` was not defined in its scope. Rather it was defined in the `add` iff conditional scope.