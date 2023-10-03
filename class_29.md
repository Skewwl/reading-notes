# 401 class_29

## useMemo

- useMemo is a React Hook that lets you cache the result of a calculation between re-renders.

- const cachedValue = useMemo(calculateValue, dependenciesArray)
  - calculateValue: The function calculating the value that you want to cache. It should be pure, should take no arguments, and should return a value of any type. React will call your function during the initial render. On next renders, React will return the same value again if the dependencies have not changed since the last render. Otherwise, it will call calculateValue, return its result, and store it so it can be reused later.
  - dependenciesArray: The list of all reactive values referenced inside of the calculateValue code. Reactive values include props, state, and all the variables and functions declared directly inside your component body.  

- Usage: Skipping expensive recalculations. Skipping re-rendering of components. Memoizing a dependency of another Hook. Memoizing a function.

## useCallback

- useCallback is a React Hook that lets you cache a function definition between re-renders.

- const cachedFn = useCallback(fn, dependenciesArray)
  - fn: The function value that you want to cache. It can take any arguments and return any values. React will return (not call!) your function back to you during the initial render. On next renders, React will give you the same function again if the dependencies have not changed since the last render. Otherwise, it will give you the function that you have passed during the current render, and store it in case it can be reused later. React will not call your function. The function is returned to you so you can decide when and whether to call it.
  - dependenciesArray: The list of all reactive values referenced inside of the fn code. Reactive values include props, state, and all the variables and functions declared directly inside your component body.
 
- Usage: Skipping re-rendering of components. Updating state from a memoized callback. Preventing an Effect from firing too often. Optimizing a custom Hook.
