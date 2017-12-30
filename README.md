# VS Code Reactjs easy snippets

## Installation

In order to install an extension you need to launch the Command Pallete
(`Ctrl + Shift + P` or `Cmd + Shift + P`) and type Extensions.

There you have either the option to show the already installed snippets or
install new ones.

## Supported languages (file extensions)

* JavaScript (`.js`)
* JavaScript React (`.jsx`)

## Snippets

Below is a list of all available snippets and the triggers of each one. The
**⇥** means the `TAB` key.

### React

| Trigger | Content                                        | Description            |
| ------: | ---------------------------------------------- | ---------------------- |
|   `ir→` | import `React`                                 | i = import, r = react  |
|  `irc→` | import `React` and `Component` constructor     | c = Compoent           |
|  `irp→` | import `React` and `PureComponent` constructor | p = PureComponent      |
|  `rfc→` | `function Component`                           |                        |
|  `rcc→` | class `Component`                              |                        |
|   `cc→` | class `constructor`                            |                        |
|   `cr→` | class `render`                                 |                        |
|  `cwm→` | class `componentWillMount`                     |                        |
|  `cdm→` | class `componentDidMount`                      |                        |
|  `crp→` | class `componentWillReceiveProps`              | r = receive, p = props |
|  `csu→` | class `shouldComponentUpdate`                  | s = should, u = update |
|  `cwu→` | class `componentWillUpdate`                    |                        |
|  `cdu→` | class `componentDidUpdate`                     |                        |
|  `cum→` | class `componentWillUnmount`                   | um = Unmount           |
|  `cdc→` | class `componentDidCatch`                      |                        |
|   `cp→` | class `this.props`                             |                        |
|   `cs→` | class `this.state`                             |                        |
|  `css→` | class `this.setState`                          |                        |
|  `cds→` | class default `state`                          |                        |
|  `cdp→` | class `static defaultProps`                    |                        |
|   `ch→` | class handler `arrow function`                 | h = handler            |

### Other

| Trigger | Content                       | Description             |
| ------: | ----------------------------- | ----------------------- |
|   `edf` | export default arrow function | e = export, d = default |

## Reference

VSCode create snippets
[Creating your own Snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

Snippets gernerator [Snippt Atom & VScode](http://snippet-generator.surge.sh/)
