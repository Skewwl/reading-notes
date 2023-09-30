# 401 class_28

## useEffect hook

- What is the main intended use case for the useEffect hook?

Some components need to stay connected to a third-party. This could be a network, library, api-- whatever. This is a way to setup connections or rerender elements based on changing variables, thus allowing your components to adapt to dynamic changes happening behind the screen.

- How does the effect’s logic interact with the component?

useEffect executes its setup function when one of its dependecy variables changes.

- What is the importance of the return value from the effect’s logic function?

The return value of useEffect has a special purpose, to cleanup any connections to uphold the integrity of a connection by staring fresh-- which could mean dropping a database table completely before adding new info to a databse.
