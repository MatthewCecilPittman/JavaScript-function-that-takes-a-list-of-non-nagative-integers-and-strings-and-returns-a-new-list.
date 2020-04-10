# JavaScript-function-that-takes-a-list-of-non-nagative-integers-and-strings-and-returns-a-new-list.
function filter_list(l){ return l.filter(x => typeof x === 'number'); } console.log(filter_list([1, 'a', 'b', 0, 15]));
