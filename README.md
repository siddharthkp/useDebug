<p align="center">
  <img src="https://octodex.github.com/images/daftpunktocat-guy.gif" height="200px"/>
  <br><br>
  <b>Custom hook to debug useEffect</b>
  <br><br>
  <a href="https://codesandbox.io/s/0qqmmv251w?moduleview=1"/>Codesandbox demo 🔗</a>
</p>

&nbsp;

Based on [Tomasz Łakomy](https://twitter.com/tlakomy)'s [egghead lesson on hooks ](https://egghead.io/lessons/react-use-react-useeffect-hook-to-see-how-many-times-component-mounts-and-unmounts)

&nbsp;

#### install

Uses the `useEffect` hook from React 16.7+

```
npm install usedebug
```

&nbsp;

#### usage

```js
import React from "react"
const useDebug = require("usedebug")

function MyComponent() {
  useDebug("mycomponent") // call useDebug with an optional id
  return <div>Hey!</div>
}
```

&nbsp;

#### like it?

:star: this repo

&nbsp;

#### license

MIT © [siddharthkp](https://github.com/siddharthkp)
