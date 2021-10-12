# ✍️ Notes
1. Class Components have a built-in object called what?
- State Object.

2. What do you store in the state object?
- Properties that belong to a particular component.

3. What happens to make the component re-render?
- When the State Object changes or updates.

4. If your component has a constructor, what needs to be passed to it?
- `props`

5. What happens if `super(props)` isn't called?
- If `super(props)`[^1] is not called, then an error will be thrown. 

6. How many properties can your state object have?
- As many as you want.

7. What happens when a value in the state object changes?
- The class is re-rendered

8. What method do you use to update the state object?
- `this.setState({})`

9. What syntax allows us to access to a value in state?
- `this.state.propertyName`

10. What does onClick do?
- when the object that has an onClick is clicked it tells the `eventListener()` to activate it's function/code

11. What kind of function do we use when defining our custom methods?
- Arrow Function `arrowFunction = () => {}`

[^1]: `super(props)` is giving properties to `react.compontent` to instantiate them.