# react-developer-snippets

Started this project from [babel-sublime-snippets](https://github.com/babel/babel-sublime-snippets) but going to tailor it to fit a better developer experience.

Will have a range of useful **React** snippets for **sublime** including unit test snippets.

## Installation

Clone this in your `Packages/User` folder and remove what you don't want.

## Support

Only the ES6 and `React 15+` versions.

## Available snippets

### React

| Trigger  | Content |
| -------: | ------- |
| `reactCreateClass→`   | class component skeleton |
| `reactStartClass`   | starting a new file with a class component skeleton |
| `didMount→`   | `componentDidMount() {…}` |
| `didUpdate→`  | `componentDidUpdate(prevProps, prevState) {…}` |
| `willMount→`   | `componentWillMount() {…}` |
| `willRecieveProps→`   | `componentWillReceiveProps(nextProps) {…}` |
| `willUnmount→`  | `componentWillUnmount() {…}` |
| `willUpdate→`  | `componentWillUpdate(nextProps, nextState) {…}` |
| `render→`   | `render() {…}` |
| `setState→`   | `this.setState(…)` |
| `shouldUpdate→`   | `shouldComponentUpdate(nextProps, nextState) {…}` |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `pt→`    | `propTypes { ... }` |
| `pta→`   | `PropTypes.arrayOf` |
| `ptai→`  | `PropTypes.arrayOf (Instances)` |
| `ptb→`   | `PropTypes.bool` |
| `pte→`   | `PropTypes.element` |
| `ptf→`   | `PropTypes.func` |
| `pti→`   | `PropTypes.instanceOf` |
| `ptn→`   | `PropTypes.number` |
| `ptn→`   | `PropTypes.node` |
| `pto→`   | `PropTypes.object` |
| `ptof→`  | `PropTypes.oneOf (Enum)` |
| `ptof→`  | `PropTypes.objectOf` |
| `ptoft→` | `PropTypes.oneOfType (Union)` |
| `pts→`   | `PropTypes.string` |
| `ptsp→`  | `PropTypes.shape` |

## Notes

  * Unsupported React API snippets: `displayName`, `forceUpdate`, `getDOMNode` (use `React.findDOMNode`), `ismounted`, `mixins`, `replaceProps`, `replaceState`, `setProps`, `statics`.

