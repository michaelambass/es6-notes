# ES6 (ECMAScript 6) Javascript - notes 

## Variables 
**var** : scoped to the nearest function block (global if outside any block)

**let** : scoped to the nearest enclosing block (global if outside any block)

**const** : scoped as let but not editable

## Arrow functions
### Function without parameters
```javascript
const getMyName = () => `Michael`;
console.log(getMyName());
```
### Function with 1 parameter 
```javascript
const setMyName = (name) => name;
console.log(setMyName('Michael Ambass'));
```

### Function with multiple parameters 
```javascript
const setMyFullname = (firstname, lastname) => firstname + ' ' + lastname;
console.log(setMyFullname('Michael', 'Ambass'));
```

### Return VS execution 
The value is automatically returned when there is no brackets.

#### Example with return 
```javascript
const getMyName = () => `Michael Ambass`;
```

#### Example with code execution 
```javascript
const getMyName = () => {

	// executed code
  	console.log('Michael Ambass');
}

getMyName();
```

