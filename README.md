#Javascript snippets for sublimetext2

A bunch of snippets for lightning-like javascripting

## Examples

Globals and word-based

```javascript
// a
arguments

// de
debugger;

// d
document

// l
location

// q
querySelectorAll('')

// w
window
```

Functions

```javascript
// f
function () {} // lots of tabstops, wraps selected text

// sif
;(function () {
	// wraps selected text
}());

// sifs
;(function () {
	'use strict';

	// wraps selected text
}());
```

Loops

```javascript
// for
for (i = 0; i < arr.length; i += 1) {
	arr[i]
} // arr and i changable
```

Timers
```javascript
// set
setTimeout(function () {}, 50);  // or
setInterval(function () {}, 50); // replace T with I while typing,
								 // and text will dynamically changed

// clr
clearTimeout();
clearInterval();
```

Logging

```javascript
// cl
console.log(); // wraps selected text

// cw
console.warn(); // wraps selected text

// ci
console.info(); // wraps selected text

// ct
console.timeStamp('');
```

Ohers

```javascript
// '
' + + ' // nice tool for string incuting

// if
if () {} // several tabstops
```
