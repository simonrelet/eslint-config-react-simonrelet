# eslint-config-react-simonrelet

> My ESLint shareable config for React style guide.

## Install

```
$ npm install --save-dev eslint eslint-config-react-simonrelet
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"scripts": {
		"lint": "eslint ."
	},
	"devDependencies": {
		"eslint": "^2.10.2",
		"eslint-config-react-simonrelet": "^0.0.2"
	},
	"eslintConfig": {
		"extends": "react-simonrelet"
	}
}
```

Then lint with `$ npm run lint`.


## License

MIT
