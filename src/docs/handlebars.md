-------------------------------
## Lipsum
-------------------------------
Handlebars helper that returns a substring of characters of lorem ipsum latin text.

-------------------------------
### Usage
-------------------------------
```javascript
{{lipsum 0 300}}
```

```javascript
{{lipsum "random" 300}}
```
-------------------------------
### Parameters
-------------------------------
##### index
Number|String "random".

The starting index. If the value is 'random' a random index will be selected.

##### length
Number|int

Number of characters to return.

-------------------------------
## Loop
-------------------------------
Handlebars helper that iterates through a range of numbers.

-------------------------------
#### Usage
-------------------------------
```javascript
{{#loop 0 5 1}}
<div>{{this}}</div>
{{/loop}}
```

Should output:

```javascript
<div>0</div>
<div>1</div>
<div>2</div>
<div>3</div>
<div>4</div>
<div>5</div>
```
-------------------------------
#### Parameters
-------------------------------
##### index
Number|int

Zero-based index at which to begin.

The starting index.

##### end
Number|int

Zero-based index at which to end extraction. slice extracts up to and including.

##### inc
Number
The number to increase by per iteration.
