## Getting a type in parameters of a function

You can use an unexported type from a module/library.

```tsx
// A function
function doSomething(a: number, b: string) {
  // Something
}

// Getting the type of `a` in the Foo function
type Foo = Parameters<typeof doSomething>["0"];
```
