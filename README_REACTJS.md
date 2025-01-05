JavaScript modules, imports-exports
1. Modules can help you to save and access your code in a more structured way.
    In general, there are two ways to exports modules in JavaScript:
        1. Using default exports.
        2. Using named exports.
    **Default exports**
    function addTwo(a,b){
        console.log(a + b);
    }
    export default addTwo;
    *Import*
    import addTwo from "./addTwo";
    **Named exports**
    export function addTwo(a,b){
        console.log(a + b);
    }
    *Import*
    import { addTwo } from "./addTwo";
2. Correct ways to declare functions in react
    2.1. 
    function MyComponent() {
        return <h1>Hello, React!</h1>
    }
3. What is the DOM? Document Object Model.
