<p align="center"><a href="https://nazmulrobin.com" target="_blank"><img src="http://laravel.nazmulrobin.com/images/nhrrob/nhrblog-logo-white.png" width="400"></a></p>

<p align="center">
<a href="https://github.com/nhrrob/javascript-interview-questions/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/nhrrob/javascript-interview-questions"></a>
<a href="https://github.com/nhrrob/javascript-interview-questions/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/nhrrob/javascript-interview-questions"></a>
<a href="https://github.com/nhrrob/javascript-interview-questions/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/nhrrob/javascript-interview-questions"></a>
<a href="https://github.com/nhrrob/javascript-interview-questions/blob/master/LICENSE.md"><img alt="GitHub license" src="https://img.shields.io/github/license/nhrrob/javascript-interview-questions"></a>

</p>

## 


In September 1995, a Netscape programmer named Brandan Eich developed a new scripting language in just 10 days. It was originally named Mocha, but quickly became known as LiveScript and, later, JavaScript. <br>

Brendan Eich is an American technologist. He co-founded the Mozilla project, the Mozilla Foundation and the Mozilla Corporation, and served as the Mozilla Corporation's chief technical officer and, briefly, as its chief executive officer. 

## 


### Table of Contents

1. Code line break
2. Comments
3. A variable without a value returns the value undefined
4. Re-declaring a variable will not destroy the value
5. Assignment Operators
6. The typeof operator returns the type of a variable or an expression
7. Adding two numbers and a string
8. Adding a string and two numbers
9. The value (and the data type) of a variable with no value is undefined
10. An empty string has both a legal value and a type

## 


### Questions & Answers
1. **Code line break** <br>
=> You can break a code line after an operator or a comma.
    ```
    <script>
    document.getElementById("demo").innerHTML =
    "Hello Dolly!";
    </script>
    ```

2. **Comments** <br>
    ```
    // Single line comment 
    /*
    Multiple line comment
    */
    ```

3. **A variable without a value returns the value undefined**

4. **Re-declaring a variable will not destroy the value**
    ```
    <script>
    var carName = "Volvo";
    var carName;
    document.getElementById("demo").innerHTML = carName;
    </script>
    ```
    Output: Volvo

5. **Assignment Operators**
    - +=
    - -=
    - *=
    - /=
    - %=

6. **The typeof operator returns the type of a variable or an expression**
    ```
    <script>
    document.getElementById("demo").innerHTML = 
    typeof "" + "<br>" +
    typeof "John" + "<br>" + 
    typeof "John Doe" + "<br>" +
    typeof 0 + "<br>" +
    typeof 314 + "<br>" +
    typeof 3.14 + "<br>" +
    typeof (3.14);
    </script>
    ```
    Output: <br>
    string <br>
    string <br>
    string <br>
    number <br> 
    number <br>
    number <br>
    number <br>

7. **Adding two numbers and a string**
<br>=> JavaScript evaluates expressions from left to right. Different sequences can produce different results:
    ```
    <script>
    var x = 16 + 4 + "Volvo";
    document.getElementById("demo").innerHTML = x;
    </script>
    ```
    Output: 20Volvo

8. **Adding a string and two numbers**
    ```
    <script>
    var x = "Volvo" + 16 + 4;
    document.getElementById("demo").innerHTML = x;
    </script>
    ```
    Output: Volvo164


9. **The value (and the data type) of a variable with no value is undefined**
    ```
    <script>
    var car;
    document.getElementById("demo").innerHTML =
    car + "<br>" + typeof car;
    </script>
    ```
    Output: <br>
    undefined <br>
    undefined <br>

10. **An empty string has both a legal value and a type**
    ```
    <script>
    var car = "";
    document.getElementById("demo").innerHTML =
    "The value is: " +
    car + "<br>" +
    "The type is: " + typeof car;
    </script>
    ```
    Output: <br>
    The value is:<br>
    The type is: string<br>


11. **TBA**
<br>=> 

## 


### License

'Javascript Interview Questions' is open-sourced project licensed under the [MIT license](https://opensource.org/licenses/MIT).

##


### Contact

Feel free to contact:  
<a href="https://www.nazmulrobin.com/">nazmulrobin.com</a> | <a href="https://twitter.com/nhr_rob">Twitter</a> | <a href="https://www.linkedin.com/in/nhrrob/">Linkedin</a> | <a href="mailto:robin.sust08@gmail.com">Email</a>

<br>

#### Reference
- https://www.w3schools.com/js/js_examples.asp