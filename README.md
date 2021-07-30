# react-ts-usestate

```js
import React, { useState } from 'react';

function Counter() {
  const [count,setCount] = useState(0);

  function increase() {
    setCount(count+1);
  }

  return(
    <div>
      My Count is {count} <br/>
      <button onClick={increase}>+</button>
    </div>
  )
}

function App() {
return (
  <div>
    <Counter/>
  </div>
);
}

export default App;

```
