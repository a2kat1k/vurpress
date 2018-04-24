---
title:  Main page
lang: en-US
---

# Main index page

<span v-for="i in 3">{{ i }} </span>

<demo />

``` js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
``` csharp
// A Hello World! program in C#.
using System;
namespace HelloWorld
{
    class Hello 
    {
        static void Main() 
        {
            Console.WriteLine("Hello World!");

            // Keep the console window open in debug mode.
            Console.WriteLine("Press any key to exit.");
            Console.ReadKey();
        }
    }
}
```

| Tables        | :clown_face:  | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

<table><tr><td>da</td></tr></table>

[Go to student](/student/)

[student heading anchor](/student/#inside-student) 
>me either
::: warning
**here be dragons**
:::
![An image](/image.jpg)
![second ow](https://source.unsplash.com/random/1920x1080)