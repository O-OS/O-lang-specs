# Specs

## Types:
```
int
float
bool
list
dict
```

## Variable declarations:
```
var <name> = <value>;
```

## If statements

```
if ( <condition> ) {
    <block>
}
```

## Loops

```
while <condition> {
    <block>
}

for <init>; <condition>; <update> {
    <block>
}

foreach <var in iterable> {
    <block>
}

do {
    <block>
} while <condition>
```

## Functions
```
func <name>( [args] ) {
    <block>
}
```

## Struct Declaration
```
struct <name> {
    <fields>
}
```

## Struct method
```
func (<name> <struct>) <name>( [args] ) {
    <block>
}
```

## Pointers
```
// assigning a pointer
var *<name> = <value>;

// referencing an object
&<variable>;
```

## Imports
```
import "<path>";

from "path" import <name>;

from "path" import <name> as <alias>;
```

## Struct Initialization
```
var x = <struct name> {
    <field_name>: <value>, ...
};
```

## Maybe more soon...