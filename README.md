## OpenModule 

OpenModule is created as example how to use land commands and import to any project you need.

### How it works

- On a project folder type `land add alqubo/OpenModule`

```ts
import { sayHi, ping } from 'alqubo/OpenModule@master/main.ts';

console.log(sayHi("Alberto"));
console.log(ping());
```

- Now, run this code with `land run main.ts`.

```sh
Hello Alberto lander!
...pong
```
Really nice, now we have this module running with __land__.
