## .closest()

Find the first matched node for each node

```js
.closest(filter);
```


### Parameters

`filter`: a string containing a selector that nodes must pass or a function that return a boolean. See [.filter()](#filter) for a better explanation



### Return

`u`: returns an instance of Umbrella JS with the new ancestors as nodes



### Examples

Get the ul of every li

```js
u("li").closest('ul');
```



### Related

- [.find(filter)](#find) get all of the descendants of the matched nodes

- [.parent(filter)](#parent) get all of the direct parents

- [.children(filter)](#children) get the direct children of all of the nodes with an optional filter
