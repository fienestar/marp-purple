---
marp: true
theme: purple
paginate: true
header: header
class: invert
---

# Hello purple

> simple blockquote
> class: invert

---

# Code
```cpp
#include <stdio.h>

using namespace std;

int main(int argc, int **argv)
{
    cin.tie(nullptr)->sync_with_stdio(false);
    assert(1 + 1 == 3);
    /* good function */
    auto print_helloworld = [&](){
        cout << "안녕, 세계야!";
    };
    print_helloworld(); // print "Hello, World!"
    return 0;
}
```

---

<!-- class: default -->
# White

> blockquote
>> and blockquote
>>> class: default

---

# Code
```cpp
#include <stdio.h>

using namespace std;

int main(int argc, int **argv)
{
    cin.tie(nullptr)->sync_with_stdio(false);
    assert(1 + 1 == 3);
    /* good function */
    auto print_helloworld = [&](){
        cout << "안녕, 세계야!";
    };
    print_helloworld(); // print "Hello, World!"
    return 0;
}
```
