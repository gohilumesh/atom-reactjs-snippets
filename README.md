# Atom Reactjs snippets

React ES6 / ES7 snippets for [Atom](https://atom.io/).

## Installation
`apm install atom-reactjs-snippets`

## Contributing

1. Fork repo
1. Create your feature branch: git checkout -b my-cool-new-feature
1. Commit your changes: git commit -m 'Such cool, much feature'
1. Push changes: git push origin my-cool-new-feature
1. Submit a pull request

# Snippets List

### Imports and DOM
| Snippet | Action |
|--------|--------|
| `ri` | `Import React` |
| `rdom` | `Import React-DOM and render to DOM` |

### Creating Components
| Snippet | Skeleton |
|--------|--------|
| `rc` | `Component Skeleton` |
| `rcc` | `Component Skeleton with Constructor` |
| `rsc` | `Stateless Component` |

### State, props and bind
| Snippet | Action |
|--------|--------|
| `rst` | `this.state` |
| `rsst` | `this.setState` |
| `rpr` | `this.props` |
| `rbi` | `bind(this) skeleton` |

### Methods
| Snippet | Method |
|--------|--------|
| `rcon` | `Constructor Method` |
| `rren` | `Render Method` |

### Component Lifecycles
| Snippet | Lifecycle |
|--------|--------|
| `cwm` | `componentWillMount` |
| `cdm` | `componentDidMount` |
| `cwr` | `componentWillReceiveProps` |
| `scu` | `shouldComponentUpdate` |
| `cwup` | `componentWillUpdate` |
| `cdup` | `componentDidUpdate` |
| `cwu` | `componentWillUnmount` |


### PropTypes
The structure of the PropTypes snippets goes like this : Use `pt` + the PropType you want to use. Add `r` at the end of the snippet to make it a required PropType. Exemple : `ptnr` will become `PropTypes.number.isRequired`. The static props and defaultprops skeletons are also included.

| Snippet | PropType |
|--------|--------|
| `sdp` | `Static default props skeleton` |
| `spt` | `Static PropTypes skeleton` |
|--------|--------|
| `pta` | `PropTypes.array` |
| `ptar` | `PropTypes.array.isRequired` |
| `ptb` | `PropTypes.bool` |
| `ptbr` | `PropTypes.bool.isRequired` |
| `ptf` | `PropTypes.func` |
| `ptfr` | `PropTypes.func.isRequired` |
| `ptn` | `PropTypes.number` |
| `ptnr` | `PropTypes.number.isRequired` |
| `pto` | `PropTypes.object` |
| `ptor` | `PropTypes.object.isRequired` |
| `pts` | `PropTypes.string` |
| `ptsr` | `PropTypes.string.isRequired` |
| `pte` | `PropTypes.element` |
| `pter` | `PropTypes.element.isRequired` |
| `ptsh` | `PropTypes.shape` |
| `ptshr` | `PropTypes.shape.isRequired` |
| `ptoo` | `PropTypes.oneOf` |
| `ptoor` | `PropTypes.oneOf.isRequired` |
| `ptoot` | `PropTypes.oneOfType` |
| `ptootr` | `PropTypes.oneOfType.isRequired` |
| `ptany` | `PropTypes.any` |
| `ptanyr` | `PropTypes.any.isRequired` |


# Licence
This project is licenced under the MIT licence, please read the licence file included in the repository for further informations.
