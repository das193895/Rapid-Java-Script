1. functions are defined in java script by using "function" key word.
    ```java script
    function add(num1 , num2){
        return num1+num2;
    }
    ```

2. functions can be assigned to variables in java script.

    ```java script
    var addition = function fn(){
        console.log("Hello");
    } 

    console.log(typeof addition); // function

    addition(); // Hello

    addition; // noting will show up because the brackets are missing so the function has never been executed.
    ```

3. We can declare the function after the function call .

    ```java script
    var ad = add(5,3);
    console.log(ad); // 

    function add(num1 , num2){
        return num1+num2;
    }
    ```