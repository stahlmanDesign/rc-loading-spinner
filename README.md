# sd-react-loading
Simple React component that shows a loading spinner and a message

# Git repository
- https://github.com/stahlmanDesign/sd-react-loading


## Usage

```
import Loading from 'sd-react-loading'

<Loading
	message={ 'Your string or component' }
	spinner={ <img src={ yourImportedGif } /> }
	className={ 'your-optional-class-names' }
	style={{ background: 'red' }}
/>
```

# As a NPM module
- Built according to this tutorial to allow publishing the ES6 React JSX code as an NPM module
- https://medium.com/@BrodaNoel/how-to-create-a-react-component-and-publish-it-in-npm-668ad7d363ce
	