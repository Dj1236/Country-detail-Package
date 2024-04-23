## Country-detail-Package


## How to use it?

You can use the project in this way:

### Install
```bash
# with npm
npm install countries-details

# with yarn
yarn add countries-details
```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'countries-details';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Republic Of India')'
```