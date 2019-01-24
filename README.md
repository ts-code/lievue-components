ts-code/lievue-components

## Installation
```
npm install ts-code/lievue-components
```
### ES6 
```js
//
// You can register a component manually
//
import { Switch } from 'ts-code/lievue-components';

export default {
  ...
  components: {
    Switch
  },
  ...
};

//
// or register the whole module with vue
//
import ModuleLibrary from 'ts-code/lievue-components';

// Install this library
Vue.use(ModuleLibrary);
```
