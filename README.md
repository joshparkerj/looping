# looping
Cataloging looping constructs in programming.

# JavaScript
```JavaScript
for (i = 0; i < 10; i++) {
 console.log(i);
}
i = 0;
while(i--){
 console.log(`John${i}`);
}
```
# C#

```C#
            string[] names = new string[5];
            int i = 0;

        startSpaghettiLoop:
            if (i < names.Length)
            {
                names[i] = "John" + ++i;
                goto startSpaghettiLoop;
            }

        startWriteLineLoop:
            if (i > 0)
            {
                Console.WriteLine(names[--i]);
                goto startWriteLineLoop;
            }
```
