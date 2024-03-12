
**React Hooks** <br>
**A React hook** is a way to add functionality to functional components in React.It's like a toolbox that provides shortcuts for common React tasks.<br>

**Use-State**.<br>
useState hook enables you to add and manage state in functional components, allowing you to create interactive and dynamic UIs.<br>
USAGE<br>
**Importing the Hook**:<br>
```import React, { useState } from 'react';```<br>
**Initializing the state**<br>
```const [state, setState] = useState(initialValue);``` <br>
state: This is the current state value.<br>
setState: This is the function you use to update the state. When you call setState, React re-renders the component with the new state value.<br>
initialValue: This is the initial value of the state variable.<br>
**Using State**<br>
```<p>Count: {state}</p>```
**Updating State**<br>
```const increment = () => {
  setState(state + 1);
};```



