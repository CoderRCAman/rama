Difference between passing dependencies in useEffect and not passing 
``
-   Giving it an empty array acts like `componentDidMount` as in, it only runs once.
    
-   Giving it no second argument acts as both `componentDidMount` and `componentDidUpdate`, as in it runs first on mount and then on every re-render.
    
-   Giving it an array as second argument with any value inside, eg `, [variable1]` will only execute the code inside your `useEffect` hook ONCE on mount, as well as whenever that particular variable (variable1) changes.