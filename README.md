# utils

## Change all functions from `PascalCase` to `snakeCase` in IntelliJ/Android Studio.
### Ignores extensions functions (containing '.')

search: `fun (\b[A-Z])+(\w+\()`

replace: `fun \l$1$2`
