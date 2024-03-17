# 1. Closures:

## A closure is a function that remembers the variables from the outer scope even after that scope has finished executing. It's like a backpack that the inner function carries around, containing all the variables it needs from the outer function. For instance, in JavaScript:

<script>
function outerFunction() {
    let outerVariable = 'Hello';
    
    function innerFunction() {
        console.log(outerVariable);
    }
    
    return innerFunction;
}

let myClosure = outerFunction();
myClosure(); // Output: Hello

</script>

## In this example, innerFunction retains access to outerVariable even after outerFunction has completed execution. This allows for powerful and flexible code structures.
