## Short React Snippets

The Short Version of React Snippets

## Snippets

| Snippet | Renders                                |
| ------- | -------------------------------------- |
| `us`    | useState                               |
| `ue`    | useEffect                              |
| `ued`   | useEffect debugging snippet            |
| `lij`   | insert console.log in JSX              |
| `dfc`   | export default fuction component       |
| `afc`   | export default arrow fuction component |
| `efc`   | export fuction component               |

## Full Expansions

us - useState

```js
const [state, useState] = useState(null);
```

ue - useEffect

```js
useEffect(() => {}, [deps]);
```

ued - useEffect debugging snippet

```js
useEffect(() => {
  console.log(variable);
}, [variable]);
```

lij - insert console.log in JSX (IIFE)

```js
{
  (() => {
    console.log(variable);
    return <></>;
  })();
}
```

dfc - export default function component

```jsx
export default function Component() {
  return <></>;
}
```

afc - export default arrow function component

```tsx
import React from "react";

interface Props {}

const Component: React.FC<Props> = ({}) => {
  return <></>;
};

export default Component;
```

efc - export function component

```jsx
function Component() {
  return <></>;
}

export { Component };
```
