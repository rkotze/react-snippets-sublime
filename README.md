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
| `reactStartFunction`   | starting a new file with a function component skeleton |
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
| `propTypes→`    | `propTypes { ... }` |
| `propTypesArrayOf→`   | `PropTypes.arrayOf` |
| `propTypesArrayOfInstances→`  | `PropTypes.arrayOf (Instances)` |
| `propTypesBool→`   | `PropTypes.bool` |
| `propTypesElement→`   | `PropTypes.element` |
| `propTypesFunc→`   | `PropTypes.func` |
| `propTypesInstanceOf→`   | `PropTypes.instanceOf` |
| `propTypesNumber→`   | `PropTypes.number` |
| `propTypesNode→`   | `PropTypes.node` |
| `propTypesObject→`   | `PropTypes.object` |
| `propTypesOneOf→`  | `PropTypes.oneOf (Enum)` |
| `propTypesObjectOf→`  | `PropTypes.objectOf` |
| `propTypesOneOfType→` | `PropTypes.oneOfType (Union)` |
| `propTypesString→`   | `PropTypes.string` |
| `propTypesShape→`  | `PropTypes.shape` |

## Notes

  * Unsupported React API snippets: `displayName`, `forceUpdate`, `getDOMNode` (use `React.findDOMNode`), `ismounted`, `mixins`, `replaceProps`, `replaceState`, `setProps`, `statics`.

