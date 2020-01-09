## Day 4 Notes

### Function declaration
> function firstfunction(/*parameters go in here */){

    console.log('this came from the firstfunction');
}

firstfunction();

### Function Parameters

> function secondfunction(num1, num2){

    console.log(num1 + num2);
}

secondfunction(1,2);


## Global vs Local variables
> Local
var global
function addtwo(num){
    var local = 2
    return num + add;
}

console.log(add);

## Fizzbuzz

function fizzbuzz(){
    for(var i = 0; i < 101; i++>)
    
    if(i % 3 === 0 && (i% 5 === 0)){
        console.log('fizzbuzz);
    }

    else if(i % 5 === 0){
        console.log('buzz);
    }

    else if(i % 3 === 0){
        console.log('fizz');
    }

    else{
        console.log(i);
    }
}