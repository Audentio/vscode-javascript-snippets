# JavaScript snippets

Go to Extensions -> Search for "audentio.audentio-javascript-snippets" and install

### General

|  Prefix | Method                                              |
| ------: | --------------------------------------------------- |
|  `imp→` | `import moduleName from 'module'`                   |
|  `imd→` | `import { destructuredModule } from 'module'`       |
|  `ime→` | `import * as alias from 'module'`                   |
|  `ima→` | `import { originalName as aliasName} from 'module'` |
|  `exp→` | `export default moduleName`                         |
|  `exd→` | `export { destructuredModule } from 'module'`       |
|  `exa→` | `export { originalName as aliasName} from 'module'` |
|  `met→` | `methodName = (params) => { }`                      |
|  `fre→` | `arrayName.forEach(element => { }`                  |
|  `fof→` | `for(let itemName of objectName { }`                |
|  `fin→` | `for(let itemName in objectName { }`                |
|  `nfn→` | `const functionName = (params) => { }`              |
|  `dob→` | `const {propName} = objectToDescruct`               |
|  `dar→` | `const [propName] = arrayToDescruct`                |
|  `sti→` | `setInterval(() => { }, intervalTime`               |
|  `sto→` | `setTimeout(() => { }, delayTime`                   |
|  `clg→` | `console.log(object)`                               |


### React

|    Prefix | Method                                                                              |
| --------: | ----------------------------------------------------------------------------------- |
|    `rcc→` | `basic react component file. imports and default class export`                      |
|    `imr→` | `import React from 'react'`                                                         |
|   `imrc→` | `import React, { Component } from 'react'`                                          |
|    `cwm→` | `componentWillMount() { }`                                                          |
|    `cdm→` | `componentDidMount() { }`                                                           |
|    `cwr→` | `componentWillReceiveProps(nextProps) { }`                                          |
|    `scu→` | `shouldComponentUpdate(nextProps, nextState) { }`                                   |
|   `cwup→` | `componentWillUpdate(nextProps, nextState) { }`                                     |
|   `cdup→` | `componentDidUpdate(prevProps, prevState) { }`                                      |
|   `cwun→` | `componentWillUnmount() { }`                                                        |
|    `sst→` | `this.setState({ })`                                                                |
|    `ssf→` | `this.setState((state, props) => return { })`                                       |
