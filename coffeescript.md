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

```coffeescript
# good
modules.exports.a = a
modules.exports.b = b
modules.exports.c = c

# bad
modules.exports.b = b
modules.exports.a = a
modules.exports.c = c

# bad
modules.exports.longModuleName = longModuleName
modules.exports.shortName = shortName
```
