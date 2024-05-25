1. Script tag is used to load java script in a web page. 
    Eg
    ```java script
    <script>
    ```
2. we can use the "src" attribute to load the javascript in another file . 
3. If a script tag contain a src attribute which is mapped to another java script file as well as has some code inside it then it will only execute the java scrpt code which is mapped through the src attribute . 
4. If we are using a script tag then always end the tag with a finishing script tag .
    Eg 
    ```java script
    <script src = "js/app.js" />  // wrong
    <script src = "js/app.js" /script>  // Right
    ```

5. If there are more than one script tags and they do not have a "defer" attribute then then will get executated in order.
6. 

    