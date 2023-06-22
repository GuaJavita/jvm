# Guajavita 


## Language Spec

### Primitive

| Primitive Type      | Size (in bytes) |
| ------------------- | --------------- |
| bool                | 1               |
| byte                | 1               |
| int8                | 1               |
| int16               | 2               |
| int32 \| int        | 4               |
| int64               | 8               |
| float32             | 4               |
| float64             | 8               |
| uint8               | 1               |
| uint16              | 2               |
| uint32 \| uint      | 4               |
| uint64              | 8               |
| ufloat32 \|float    | 4               |
| ufloat64 \|double   | 8               |
| char                | 4               |

### Variables
**All Variables are unmutable**, therefor they have to be initialized 
```
var x int32 = 123;
var y int = 0xFFF;
```

### Control Flow

### If

```
if boolean  {
statements
} else if boolean {
statements
} else {
statements
}
```

**guaJavita is an opinionated language, opening braces must be in the same line**

### for loop

```
var letters []char = ["A","B","C","👾","た"];
for (var i = 0; i < letters.length; i++) {
  print(letters[i] + "<be>");
} 
```


# Why 
![Why? For the glory of Satan of course](./img/wftgosoc.jpg)
