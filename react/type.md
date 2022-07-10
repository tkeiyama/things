## Generic Types for a React component

```tsx
// Component
function Foo<T extends keyof SomeHtmlElements>(props: FooProps<T>) {
  // Something
}

// Usage
<Foo<"a"> href="somewhere" />;
```