# Guajavita 


## Language Spec

### Primitive

| Primitive Type      | Size (in bytes) |
| ------------------- | --------------- |
| bool                | 1 *bit               |
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
**All Variables are immutable**, therefor they have to be initialized 
```
var x int32 = 123;
var y int = 0xFFF;
```

### Arrays

```
var primes []int =[2, 3, 5, 7, 11, 13]
```

### Control Flow
**Guajavita is an opinionated language, opening braces must be in the same line**

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



### for loop

```
var letters []char = ["A", "B", "C","👾", "た"];
for (var i = 0; i < letters.length; i++) {
  print(letters[i] + "<be>");
} 
```

### while 
```
while boolean {
 statements
}
```

## Functions
All Guajavita must return a value, that value must be handle by the caller. 

```
func add(x int, y int) int {
  return x+y;
}

int main () {
 var result = add(1,2);
 print(result);
}
```

```
func add(x int, y int) int {
  return x+y;
}

int main () {
 var result = add(1,2);
 print(result);
}
```

# Why 
![Why? For the glory of Satan of course](./img/wftgosoc.jpg)
