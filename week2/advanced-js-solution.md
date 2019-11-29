# Advanced JavaScript solutions

This is the solution for the advanced JavaScript workshop, only look at it in case you have solved the question and want to check different solutions.

- Count the divisible numbers

This is your typical for loop case, you need to loop over the numbers and check which are divisible by k

```js
function divisibleCount(x, y, k) {
  var count = 0;
  for (var i = x; i <= y; i++) {
    if (i % k === 0) {
      count++;
    }
  }
  return count;
}
```

The more mathematical solutions

```js
function divisibleCount(x, y, k) {
  return Math.floor(y / k) - Math.floor((x - 1) / k);
}
```

- Sorting arrays alphabetically

The following solution is sorting the array by always comparing the first letter of each 2 words lower-cased:

```js
// input: names - unsorted strings
// output: case-agnostic sort
sortme = function(names) {
  return names.sort(function(a, b) {
    var letter1 = a.toLowerCase().charAt(0);
    var letter2 = b.toLowerCase().charAt(0);
    return CompareForSort(letter1, letter2);
  });
};

function CompareForSort(first, second) {
  if (first == second) return 0;
  if (first < second) return -1;
  else return 1;
}
```
