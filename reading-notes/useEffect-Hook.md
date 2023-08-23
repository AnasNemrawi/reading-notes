
# Component Lifecycle ( useEffect Hook )





1. What is the main intended use case for the useEffect hook?
- Managing side effects in functional components.

2. How does the effect’s logic interact with the component?
- Cleanup: The effect's logic can return a cleanup function. This function is used to clean up any resources that the effect might have created during its execution


- Execution Timing: The effect's logic function is executed after the component renders. This means it runs both after the initial render and after every subsequent re-render

3. What is the importance of the return value from the effect’s logic function?
- The return value from the effect's logic function is of great importance for managing the lifecycle of the side effect. This returned value is often referred to as the "cleanup function."
