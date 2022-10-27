```js
import identifier from 'moduleName';
import * as name from 'moduleName';
import { identifier } from 'moduleName';
import { identifier as alias } from 'moduleName';
import { name1, name2 } from 'moduleName';
import 'moduleName'; // файл просто исполнится

export default identifier;
export { name1, name2 };
export { variable1 as name1, variable2 as name2 };
export const object1 = {};
```