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
