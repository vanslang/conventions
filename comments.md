# Comments

### Single Line Comments
As usual.
```
// Hello world
```

### Multi-Line Comments
Text should start without spaces.
The closing comment syntax should end on same final line of the text.
```
/* 
Text should start without spaces.
The closing comment syntax should end on same final line of the text. */
```


### Functions Comments
Functions comments should be structured.
```
/*
<Description>
- <Parameter> - <Shorthand-type> - <Parameter-description>
- ""  - ""  - ""
- Return - <Shorthand-type> - <Return-description> */
```

### Common Types 
| Shorthand| Type    |
| :---     | :----:  |
| u        | Undefined|      
| b        | Boolean |
| n        | Number  |
| B        | BigInt  | 
| s        | String  |
| $        | Symbol  |
| f        | Function|
| o        | object  |
| A        | Array   |
| N        | Null  |
| nN       | NaN |

### Object Types 
For additional types of objects, the object should be defined in the parameter-description.

```
- pattern - o - RegExp: <Pattern description>
```

### Union Types
Use the `|` to imply multiple types
```
- value - A|n|s - <Value description> 
```
Union Types with object types can be defined similarly
```
- value - o|o|o|s - WeakMap, o, RegExp, s: <Value description>
```
