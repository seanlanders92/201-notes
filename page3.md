### Day 3 Notes.

#### Arrays.
>start at the 0 position 
>for loop ex for(var i =0; i<10; i++)

> JS demo
var userscore = 0;
var questions = ["Where did you grow up?", "What was your childghood pet", "What was your bday month"];
var answers = ['atlanta', 'otto the goldfish', 'october'];
var response = "";

for(var i = 0; i < questions.length; i++){
    response = prompt(questions[i]);
    if(response.toLowerCase() === answers[i].toLowerCase()){
        alert('correct');
        userscore++;
    } else {
        alert('Wrong');
    }
}

alert('you got ' +userscore+ 'correct, out of' +questions.length);


#### HTML elements
> types of positions: absolute: positioned relative to other elements.
                    relative: positioned relative to itself. 
                    fixed:
                    static: