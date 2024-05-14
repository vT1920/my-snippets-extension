
## Installation

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code

## Supported languages (file extensions)
* JavaScript (.js)
* TypeScript (.ts)
* JavaScript React (.jsx)
* TypeScript React (.tsx)
* Html (.html)
* Vue (.vue)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Import and export
| Trigger  | Content |
| -------: | ------- |
| `imp→`   | imports entire module `import fs from 'fs';`|
| `imn→`   | imports entire module without module name `import 'animate.css'` |
| `imd→`   | imports only a portion of the module using destructing  `import {rename} from 'fs';` |
| `ime→`   | imports everything as alias from the module `import * as localAlias from 'fs';` |
| `ima→`   | imports only a portion of the module as alias `import { rename  as localRename } from 'fs';` |
| `rqr→`   | require package `require('');`|
| `req→`   | require package to const `const packageName = require('packageName');`|
| `mde→`   | default module.exports `module.exports = {};`|
| `env→`   | exports name variable `export const nameVariable = localVariable;` |
| `enf→`   | exports name function `export const log = (parameter) => { console.log(parameter);};` |
| `edf→`   | exports default function `export default function fileName (parameter){ console.log(parameter);};` |
| `ecl→`   | exports default class `export default class Calculator { };` |
| `ece→`   | exports default class by extending a base one `export default class Calculator extends BaseClass { };` |

### Class helpers
| Trigger  | Content |
| -------: | ------- |
| `con→`   | adds default constructor in the class `constructor() {}`|
| `met→`   | creates a method inside a class `add() {}` |
| `pge→`   | creates a getter property `get propertyName() {return value;}` |
| `pse→`   | creates a setter property `set propertyName(value) {}` |

### Various methods
| Trigger  | Content |
| -------: | ------- |
| `fre→`   | forEach loop in ES6 syntax `array.forEach(currentItem => {})`|
| `fof→`   | for ... of loop `for(const item of object) {}` |
| `fin→`   | for ... in loop `for(const item in object) {}` |
| `anfn→`  | creates an anonymous function `(params) => {}` |
| `nfn→`   | creates a named function `const add = (params) => {}` |
| `dob→`   | destructing object syntax `const {rename} = fs` |
| `dar→`   | destructing array syntax `const [first, second] = [1,2]` |
| `sti→`   | set interval helper method `setInterval(() => {});` |
| `sto→`   | set timeout helper method `setTimeout(() => {});` |
| `prom→`  | creates a new Promise `return new Promise((resolve, reject) => {});`|
| `thenc→` | adds then and catch declaration to a promise `.then((res) => {}).catch((err) => {});`|

### Console methods
| Trigger  | Content |
| -------: | ------- |
| `cas→`   | console alert method `console.assert(expression, object)`|
| `ccl→`   | console clear `console.clear()` |
| `cco→`   | console count `console.count(label)` |
| `cdb→`   | console debug `console.debug(object)` |
| `cdi→`   | console dir `console.dir` |
| `cer→`   | console error `console.error(object)` |
| `cgr→`   | console group `console.group(label)` |
| `cge→`   | console groupEnd `console.groupEnd()` |
| `clg→`   | console log `console.log(object)` |
| `clo→`   | console log object with name `console.log('object :>> ', object);` |
| `ctr→`   | console trace `console.trace(object)` |
| `cwa→`   | console warn `console.warn` |
| `cin→`   | console info `console.info` |
| `clt→`   | console table `console.table` |
| `cti→`   | console time `console.time` |
| `cte→`   | console timeEnd `console.timeEnd` |


### HTML Snippets

| Trigger              | Content                                             |
| -------------------- | --------------------------------------------------- |
| `a-class`            | `[class]` binding                                   |
| `a-select`           | `<select>` control                                  |
| `a-style`            | `[style]` binding                                   |
| `a-ngClass`          | `ngClass`                                           |
| `a-ngFor`            | `*ngFor`                                            |
| `a-ngForAsync`       | `*ngFor` with async                                 |
| `a-ngFor-trackBy`    | `*ngFor` with trackBy                               |
| `a-form`             | create a form tag with ngSubmit and form attributes |
| `a-formArrayName`    | `formArrayName`                                     |
| `a-formControlName`  | `formControlName`                                   |
| `a-formGroup`        | `formGroup`                                         |
| `a-formGroupName`    | `formGroupName`                                     |
| `a-form-submit`      | create a submit button for a form                   |
| `a-ngIf`             | `*ngIf`                                             |
| `a-ngIfElse`         | `*ngIf` with `else`                                 |
| `a-ngModel`          | `ngModel`                                           |
| `a-routerLink`       | `routerLink`                                        |
| `a-routerLink-param` | `routerLink` with a route parameter                 |
| `a-ngStyle`          | `ngStyle`                                           |
| `a-ngSwitch`         | `ngSwitch`                                          |
| `a-prej`             | show the JSON form of a model                       |
| `a-preja`            | show the JSON form of a model, using async          |
| `a-ng-container`     | `<ng-container>` element                            |
| `a-ng-template`      | `<ng-template>` element                             |
| `a-ng-content`       | `<ng-content>` element                              |


### TypeScript Angular Snippets

| Trigger                      | Content                                                              |
| ---------------------------- | -------------------------------------------------------------------- |
| `a-component`                | component                                                            |
| `a-component-standalone`     | standalone component                                                 |
| `a-component-inline`         | component with inline template                                       |
| `a-component-root`           | root app component                                                   |
| `a-ctor-skip-self`           | angular `NgModule`'s `skipself` constructor                          |
| `a-directive`                | directive                                                            |
| `a-guard-can-activate`       | `CanActivate` guard                                                  |
| `a-guard-can-activate-child` | `CanActivateChild` guard                                             |
| `a-guard-can-deactivate`     | `CanDeactivate` guard                                                |
| `a-guard-can-match`          | `CanMatch` guard                                                     |
| `a-httpclient-get`           | `httpClient.get` with Rx Observable                                  |
| `a-http-interceptor`         | Empty Angular `HttpInterceptor` for `HttpClient`                     |
| `a-http-interceptor-headers` | Angular `HttpInterceptor` that sets headers for `HttpClient`         |
| `a-http-interceptor-logging` | Angular `HttpInterceptor` that logs traffic for `HttpClient`         |
| `a-module`                   | module                                                               |
| `a-module-root`              | root app module                                                      |
| `a-output-event`             | `@Output` event and emitter                                          |
| `a-pipe`                     | pipe                                                                 |
| `a-preload-opt-in-strategy`  | custom preload strategy that allows choosing which routes to preload |
| `a-preload-network-strategy` | custom preload strategy that preloads based on network connectivity  |
| `a-resolver`                 | resolver                                                             |
| `a-routes`                   | Route definition file                                                |
| `a-rxjs-import`              | import RxJs features                                                 |
| `a-rxjs-operators`           | import RxJs operators                                                |
| `a-route-path-404`           | 404 route path                                                       |
| `a-route-path-default`       | default route path                                                   |
| `a-route-path-with-children` | route path with children                                             |
| `a-route-path-eager`         | eager route path                                                     |
| `a-route-path-lazy`          | lazy route path                                                      |
| `a-router-events`            | listen to one or more router events                                  |
| `a-route-params-subscribe`   | subscribe to route parameters                                        |
| `a-service`                  | service with injectable provided in root                             |
| `a-service-httpclient`       | service with `HttpClient`                                            |
| `a-subscribe`                | Rx Observable subscription                                           |
| `a-trackby`                  | to create a trackby function in TypeScript for the `ngFor`           |

[code]: https://code.visualstudio.com/
