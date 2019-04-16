# JSON
* json stands for: `Java Script Object Notation`
* every json object is wrapped with `{` `}`
* every json object has properties
* every property in json object, is created by 2 parts:
    * `key` - is a string
    * `value` - can be any type (e.g: number, string, boolean, array ...)
* between each `key` and `value` we add `:`
* between one property to another, we add `,`
* for example, a simple student is represented in json this way:
    ```json
    {
        "age":40,
        "name":"Bob"
    }
    ```
* in js we can access the properties this way:
    ```javascript
    var s={
        "age":40,
        "name":"Bob"
    };

    console.log(s.age)     // --> 40
    console.log(s["age"])  //--> 40      
    ```