# Generate URL query string string from oject

Generates a query string from a object

### Usage

```
import generateQueryString from 'generate-query-string'
```

```
const obj = {
	a: '1',
	b: '2',
	c: '3'
}

const makeString = generateQueryString(obj)
```

```
Output : 

console.log(makeString)

'?a=1&b=2&c=3'

```


Please note:

`encodeURIComponent` has been applied to both key and values so `decodeURIComponent` will need to applied to any special characetsr in the key and values



## Authors

*   **Luke Robertson** - [DesignAlchemy](https://github.com/designalchemy/)

## License

Public
