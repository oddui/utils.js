utils.js
========

Super small javascript library that simplifies HTML document traversing, ajax interactions and other common tasks.

A [test suite](http://utilsjs.herokuapp.com/test/index.html) is included for your perusal.

Usage
-----

Create a utils.js object

    var $ = utils();

Select elements

    // select all <p> elements
    $('p');
    
    // $('selector') returns an array of DOM elements.
    // See the [Element API](https://developer.mozilla.org/en-US/docs/Web/API/Element).

    // select all <p> elements in the first <div> element
    $('p', $('div')[0]);

Common utilities

    // an emtpy function
    $.emtpy

    // detect object type
    $.toType({}); // object
    $.toType([]); // array

    // 

Query

    // 

Element

    // 

Output

    // 

Styles

    // 

Ajax    

    // 
