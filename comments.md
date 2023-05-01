# Comments

### Single Line Comments
As usual.
```
// Hello world.
```

### Multi-Line Comments
The text should start without spaces.
The closing comment syntax should end on the same final line of the text.
```
/* 
The text should start without spaces.
The closing comment syntax should end on the same final line of the text. */
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
To include more types of objects, specify their definitions in the parameter description.

```
- pattern - o - RegExp: <Pattern description>
```

### Union Types
Use the `|` to imply multiple types
```
- value - A|n|s - <Value description> 
```
Union-types containing object types can be defined in the parameter description relatively.
```
- value - o|o|o|s - WeakMap, o, RegExp, s: <Value description>
```
