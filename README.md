# React Bookmarklet Maker
React in a bookmarklet  

Paste the following into https://zvakanaka.github.io/react-bookmarklet-maker:
```jsx
function App() {
  const [counter, setCounter] = React.useState(1)
  
  return (
    <div>
       <button onClick={() => setCounter(counter + 1)}>Increment</button>
       <p>{counter}</p>
    </div>
  )
}

ReactDOM.render(
  <App />,
  document.getElementById('root')
)
```
