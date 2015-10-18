# regexjs
The negation of an empty space 

```javascript
  function getString(){
    var stringRecieved = document.getElementsByName('stringvar')[0].value;
    var myRe = /^^$/g
    var myArray = myRe.exec(stringRecieved);
    console.log( 'array val ', myArray );
    console.log('string val ', stringRecieved);
  }
```
