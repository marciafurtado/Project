# Project
Javascript exercise provided by Ironhack


function mathGame(arrLength){
    var gameArray = [];

    for (var i = 1; i <= arrLength; i++){
        if (i % 3 === 0 && i % 5 === 0){
            gameArray.push("FizzBuzz");
        } else if (i % 3 === 0){
            gameArray.push("Fizz");
        } else if (i % 5 === 0){
            gameArray.push("Buzz");
        } else {
            gameArray.push(i);
        }
    }
   
return gameArray; 
}


mathGame(100)
