## print ints from 0 to 5

```
{
    for (let i = 0; i < 5; i++) {
        console.log(i);
    }
}
```

## list of 10 ints, * 3, filter out even numbers

```
{
    const is = Array.from({length: 10}, (_, i) => i);
    is
    .map(i => i * 3)
    .filter(i => i % 2 !== 0)
    .forEach(i => console.log(i));
}
```


## create list of ints between 0 and 5

```
{
    const is = Array.from({length: 5}, (_, i) => i);
    console.log (is);
}
```

## create map of string to number

```
{
    const theMap = new Map();
    const is = Array.from({length: 5}, (_, i) => i);
    is.forEach(i => theMap.set("i", i));
    console.log(theMap);
}
```

## declare function

```
function f (param) {
    console.log({param});
}
f(10);
```

## declare constant

```
const c = (param) => {
    console.log(param);
}
c(10)
```

## list of 10 ints, * 3, filter out even numbers

```
{
    const is = Array.from({length: 10}, (_, i) => i);
    is.map(i => i * 3).filter(i => i % 2 !== 0).forEach(i => console.log(i));
}
```

## function throws exception, call inside a try

```
{
    function throwIt() {
        throw 'error';
    }
    try {
        throwIt();
        console.log(`error: ${error} -- no catch`);
    } catch (e) {
        console.log(`catch: ${e}`);
    }
}
```

## pass function as a parameter to another function

```
{
    function passed() {## I'm passed");}
    function passedToo() {## I'm passedToo");}
    function caller(f) {
        f();
    }
    caller(passed);
    caller(passedToo);
}
```
