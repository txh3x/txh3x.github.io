+++
title = 'Init'
date = 2024-11-09T14:41:29+05:30
draft = true
+++

## Init

This is my first post.

**C**

```c
#include <stdio.h>
#define FORMAT_SPECIFIER "%s\n"

int main(int argc, char** argv){
    char* msg = "olleh";
    printf(FORMAT_SPECIFIER, msg);
}
```

**Cpp**

```cpp
#include <iostream>

int main(int argc, char** argv){
    std::string msg = "olleh";
    std::cout <<  msg << std::endl;
}
```

**Python**

```py
print("olleh");
```

**Rust**

```rs
fn main(){
    let msg = String::from("olleh");
    println!("{}", msg);
}
```

**Nim**

```nim
echo "olleh"
```
