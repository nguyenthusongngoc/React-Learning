Install :
  npm i

useSelector() => get value from Store

useState(state, action) => create a state and set state with action

useEffect(() => {
  effect
  // Look like componentDidMount()
  return () => {
    cleanup
    // Look like componentWillUnmount()
  }
}, [input]); 
=> follow dependencies [input] useEffect will re-render:
    no [input] -> render all time
    [input] -> re-render when [input] change
    [] -> render one time
