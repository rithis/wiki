```coffeescript
# good
longVariableName = 1
short = 2

# bad
short = 2
longVariableName = 1

# bad
longVariableName = 1
short            = 2
```

```coffeescript
# good
stringVariable = "string"

# good
stringVariable = "#{a}#{b}"

# bad
stringVariable = 'string'

# bad
stringVariable = a + b
```
