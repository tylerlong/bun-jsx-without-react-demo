# bun JSX without React Demo

```
bun index.tsx
```

## without `tsconfig.json` file

Output:

```
{
  $$typeof: Symbol(react.transitional.element),
  type: "div",
  key: null,
  props: {},
  _owner: null,
  ref: null,
  _store: {
    validated: 0,
  },
  _debugInfo: null,
}
```

## with `tsconfig.json` file

Output:

```
hello world
```
