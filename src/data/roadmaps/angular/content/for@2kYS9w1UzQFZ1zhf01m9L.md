# @for

The @for block repeatedly renders content of a block for each item in a collection.

# Example

```
@for (item of items; track item.name) {
<li>{{ item.name }}</li>
} @empty {
<li>There are no items.</li>
}
```

Visit the following resources to learn more:

- [@official@Angular Official Docs - @for](https://angular.dev/api/core/@for)
