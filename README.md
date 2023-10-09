
               ===>    Question Number - 1 <===

                let greeting;
                greetign = {};
             console.log(greetign);

             A: {}
             B: ReferenceError: greetign is not defined
             C: undefined


    (Answer) ==> B: ReferenceError: greetign is not defined

                  Here is the Explanation

  The code contains a typographical error (greetign instead of greeting), which results in a ReferenceError because greetign is not a defined variable.




                     ===>    Question Number - 2 <===

                     function sum(a, b) {
                        return a + b;
                        }

                        sum(1, "2");


                        A: NaN
                        B: TypeError
                        C: "12"
                        D: 3

                  (Answer) ==> A: NaN


                    Here is the Explanation

  The code attempts to add a number and a string, resulting in a Not-a-Number (NaN) value because JavaScript cannot perform arithmetic operations between different data types without explicit type conversion.



                  ===>    Question Number - 3 <===

                        const food = ["🍕", "🍫", "🥑", "🍔"];
                        const info = { favoriteFood: food[0] };

                        info.favoriteFood = "🍝";

                        console.log(food);
                        A: ['🍕', '🍫', '🥑', '🍔']
                        B: ['🍝', '🍫', '🥑', '🍔']
                        C: ['🍝', '🍕', '🍫', '🥑', '🍔']
                        D: ReferenceError 


                      (Answer) ==> A: ['🍕', '🍫', '🥑', '🍔']


                        Here is the Explanation

                The code modifies the info.favoriteFood property 
                but does not affect the food array.





                ===>    Question Number - 4 <===

                            function sayHi(name) {
                            return `Hi there, ${name}`;
                            }

                            console.log(sayHi());
                            A: Hi there,
                            B: Hi there, undefined
                            C: Hi there, null
                            D: ReferenceError 

                      (Answer) ==> B: Hi there, undefined


                        Here is the Explanation

                  The function sayHi expects an argument name, 
               but when called without any arguments, name is undefined.


                 ===>    Question Number - 5 <===

                         
                        let count = 0;
                            const nums = [0, 1, 2, 3];

                            nums.forEach((num) => {
                            if (num) count += 1;
                            });

                            console.log(count);
                            A: 1
                            B: 2
                            C: 3
                            D: 4

                      (Answer) ==> B: 3 


                        Here is the Explanation

                The forEach loop iterates over each element in the nums array. The condition if (num) evaluates to true for the elements 1, 2, and 3, so the count variable is incremented three times, resulting in a final value of 2.


             






















                           