
```sh
$ npm ci
$ npx tsc --noEmit
index.ts:2:9 - error TS2614: Module '"@lib"' has no exported member 'foo'. Did you mean to use 'import foo from "@lib"' instead?

2 import {foo} from "@wild"; // ts(2614): Module '"@lib"' has no exported member 'foo'. Did you mean to use 'import foo from "@lib"' instead?
          ~~~


Found 1 error in index.ts:2
```
