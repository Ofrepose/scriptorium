# Scriptorium
This script simplifies the use of console.log and gives it debug power.

## Installation

Simply import into your project


## Usage
pt("description to print", <objectYouDescribed[optional]>, <debug[boolean-optional]>);\
ie: const exampleObject = [5, 10, "Example", 0];

```javascript
pt("The value of Example Object is: ", exampleObject, true);
```
Result:
```
Debug Name:: The value of Example Object is: 

Type: object
isArray?:: true
Value: 5,10,Example String inside array,0
Length: 4
 
Attempting to map over object::
5
10
Example String inside array
0
::Map over Object completed

Attempting to get key|value pairs::
0: E
1: x
2: a
3: m
4: p
5: l
6: e
::Attempt complete
```

```javascript
pt("The value of Example Object is: ", exampleObject);
```
Result:
```
The value of Example Object is: 5,10,Example,0
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
