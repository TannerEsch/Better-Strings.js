# Better-Strings.js
```javascript

String.prototype.reverse();
--------------------------

#Type: reverse(): String;
#Notes: reverses the string
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.reverse();
        output ---> 321cbazyx si eman ym ih

    ----------------------- demo -----------------------

String.prototype.countWords(n: number) 
--------------------------

#Type: countWords(): Number;
#Notes: Counts the number of strings seperate by spaces in a given string;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.countWords();
        output ---> 5

    ----------------------- demo -----------------------

String.prototype.isPalindrome() 
--------------------------

#Type: isPalindrome(): Boolean;
#Notes: returns true or false based on whether or not a string is palindromic, regardless of spaces and capitalization;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'
        
        str.isPalindrome();
        output ---> false

        let str2 = "poor dan is in a droop"

        str2.isPalindrome()
        output ---> true

    ----------------------- demo -----------------------

