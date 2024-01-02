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
Functions comments should be structured:
```
/*
<Description>
- <Parameter> - <Shorthand-type> - <Parameter-description>
- ""  - ""  - ""
- Return - <Shorthand-type> - <Return-description> */
```
Parameter and return descriptons are optional.

### Common Types 
| Shorthand| Type    |
| :---         | :----:  |
| undefined    | Undefined|      
| boolean      | Boolean |
| number        | Number  |
| Bigint        | BigInt  | 
| string        | String  |
| symbol        | Symbol  |
| function        | Function|
| object        | object  |
| array        | Array   |
| null         | Null  |
| nan          | NaN |
| regexp       | RegExp 

### Object Types 
To include more types of objects, specify their definitions in the parameter description.

```
- pattern - object - RegExp: <Pattern description>
```

### Union Types
Use the `|` to imply multiple types
```
- value - array|number|string - <Value description> 
```
Union-types containing object types can be defined in the parameter description relatively.
```
- value - object|object|string - weakmap, object, regexp, string: <Value description>
```
