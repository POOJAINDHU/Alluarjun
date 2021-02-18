# alluarjun

###function
function addition(){
    var a=10;
    var b=20;
    return a+b
}
addition()
30
```
function wth parameters
```javascript
function addition(a,b){
    return (a+b)
}
addition(2,3)
```
function with parameter
```javascript
function multiplication(a,b){
    return(a*b)
}
multiplication(5,2)
```
anoymous function

```javvar sub=function(a,b){
    return(a-b)
}
sub(8,4)ascript
```
arrow function
```javascript
var mul=function(a,b){
    return (a*b)
}

mul(2,3)
6
var mul=(a,b)=>{
    return (a*b)
}

mul(2,3)
6
```
### Higher order function(HDF)
*A function accepts another function as an argument

arr.map((item,index)=>{
    console.log(item+"is having index of:"+index)
})
