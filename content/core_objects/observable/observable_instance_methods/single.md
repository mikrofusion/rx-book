# single

`Rx.Observable.prototype.single([predicate], [thisArg])`
<a href="#rxobservableprototypesinglepredicate-thisarg">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/single.js "View in source") 

Returns the only element of an observable sequence that satisfies the condition in the optional predicate, and reports an exception if there is not exactly one element in the observable sequence.
 
#### Arguments
1. `[predicate]` *(`Function`)*: A predicate function to evaluate for elements in the source sequence. The callback is called with the following information:
    1. the value of the element
    2. the index of the element
    3. the Observable object being subscribed
2. `[thisArg]` *(`Any`)*: Object to use as `this` when executing the predicate.

#### Returns
*(`Observable`)*: Sequence containing the single element in the observable sequence that satisfies the condition in the predicate.

#### Example

##### No Match

[](http://jsbin.com/jonuso/1/embed?js,console)    

##### Without a predicate

[](http://jsbin.com/hoceb/1/embed?js,console)

##### With a predicate

[](http://jsbin.com/gekak/1/embed?js,console) 

##### More than one match

[](http://jsbin.com/wuqel/1/embed?js,console)

### Location

File:
- [`/src/core/observable/single.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/single.js)

Dist:
- [`rx.aggregates.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.aggregates.js)

Prerequisites:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Aggregates`](http://www.nuget.org/packages/RxJS-Aggregates/)

Unit Tests:
- [`/tests/observable/single.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/single.js)