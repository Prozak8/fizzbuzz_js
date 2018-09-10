Question 1: 
    To the best of your knowledge please explain what the following lines of code do

let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js');
eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)

Answer 1:
    fizzBuzz is the variable assigned to reading the specified file within the brackets and evaluating whatever is exported as FizzBuzz.

Question 2:
    To the best of your knowledge please explain why we are placing the *let fizzBuzz = new FizzBuzz* outside the *it* block?

Answer 2:
    It's like in Ruby when we create an instance double. fizzBuzz starts lowercase and it equals to 'new FizzBuzz.' For testing purposes and readability we are creating an instance of FizzBuzz.

Question 4:
     To the best of your knowledge please explain why we are moving (number % 5 === 0) to the top?

Answer 4:
    Because, like how we get bank notes from an atm, we must check if we can get a larger note first before smaller notes. It just makes sense to check if something has a larger common denominator first.

Question 5: 
    To the best of your knowledge please explain the difference between feature and unit test.

Answer 5:
    A feature, by definition, is an extension or being hosted by a third party. Like when an artist features on another artists song. A feature test in this context would be the test hosted on a web server.

Question 6: 
    To the best of your knowledge please explain what expectations in the context of testing are.

Answer 6: 
    The expectations in the context of testing are that when provided with the scenario, functionality is tested. If I provide a number and hit enter will the function trigger and produce a result according to my function description? The expectations are results that we deem fit before continuing with adding more layers of code. 

Question 7: 
    To the best of your knowledge please write a line to line explanation of what is happening in this code.

Answer 7:
    The script is called upon first to determine the number. The next script has an EventListener which 'listens' or takes the number from the LoadedContent, passes it through the button which displays the number, puts the answer in the new div, the value is checked against what it should display.






