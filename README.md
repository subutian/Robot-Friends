## Robot-friends

https://euphonious-griffin-e6449b.netlify.app

**Basic Introduction:** 

The name of the project is Robot Friends, a front-end web page built with React. 

Function 1: When the user enters the website, the page will first show all the robots information in the form of cards. 

Function 2: When the user searches in the search box, the page will dynamically match the keywords and display the cards corresponding to the keywords.

**Project Benefits**. 

Firstly, using flexbox layout, the page dynamically adapts to different sizes of mobile phones, tablets and desktops. In the react part , using the React function component . Which uses two hooks, one is useState, one is useEffect, useState to manage state variables, useEffect to deal with side effects. 

In the fetch data part, used Async/Await to fetch public API data, at the same time in the asynchronous function inside the Try/Catch error handling. When the server returns a 200 HTTP status code, the request was successful. For example, the server may return 404 (not found), 500 (internal server error) and so on.

**Project Challenge**. 

The original project used React Class class component , I used React Function component to upgrade the original class class component , so that the code is more concise , easy to understand , easy to maintain later. 

Get data originally used Promise .then the form of the original procedure and did not carry out error handling, based on this, I used Async/Await rewrite, while adding the error handling Try/Catch.
