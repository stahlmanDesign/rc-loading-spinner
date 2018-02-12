# sd-react-loading
Simple React component that shows a loading spinner and a message

# Git repository
- https://github.com/stahlmanDesign/sd-react-loading

# Installation
- `npm install --save sd-react-loading`

## Usage

- All arguments are optional
- Defaults:
	- **message**: **Loading…**
	- **spinner**: `<i className='fa fa-spinner'/>` (if FontAwesome 4.x is installed)
	- **className**: ''
	- **style**: {}
	
```
import Loading from 'sd-react-loading'

<Loading
	message={ 'Your string or component' }
	spinner={ <img src={ yourImportedGif } /> }
	className={ 'your-optional-class-names' }
	style={{ background: 'red' }}
/>
```

# Modifications
- place the folder in your React project and `import Loading from '`…your path here…`../src/index.js'`


# As an NPM module
- Built according to this tutorial to allow publishing the ES6 React JSX code as an NPM module
- https://medium.com/@BrodaNoel/how-to-create-a-react-component-and-publish-it-in-npm-668ad7d363ce
	