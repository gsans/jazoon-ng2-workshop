#Jazoon | Workshop - Angular 2

[![Join the chat at https://gitter.im/gsans/jazoon-ng2-workshop](https://badges.gitter.im/gsans/jazoon-ng2-workshop.svg)](https://gitter.im/gsans/jazoon-ng2-workshop?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Instructions and Setup](http://bit.ly/jazoon-workshop-doc)

> Based on https://github.com/angular-class/angular2-webpack-starter.

```
jazoon-ng2-workshop/
 ├──src/                       
 |   ├──main.ts                * entry file
 │   │
 |   ├──index.html             * index page
 │   │
 │   ├──my-app/                * basic application to explore Angular 2 features.
 │   │
 │   └──simple-app/            * simple hello world root component.
 │   │
 │   └──app/                   * original app from angular2-webpack-starter.
```

You can easily switch between them or add your own by changing the *root component* import in `src/main.browser.ts` (line 16). 

```
//src/main.browser.ts

12 /*
13 * App Component
14 * our top level component that holds all of our components
15 */
16 import {App, APP_PROVIDERS} from './my-app';
```

# License
 [MIT](/LICENSE)