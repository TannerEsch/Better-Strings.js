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
        output ---> '321cbazyx si eman ym ih'

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

String.prototype.toPascalCase() 
--------------------------

#Type: toPascalCase(): Boolean;
#Notes: capitalizes the first letter of every word in a given string;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.toPascalCase();
        output ---> 'Hi My Name Is Xyzabc123'

    ----------------------- demo -----------------------

String.prototype.toCamelCase() 
--------------------------

#Type: toCamelCase(): Boolean;
#Notes: capitalizes the first letter of every word in a given string, (except for the first word in the string);
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.toCamelCase();
        output ---> 'hi My Name Is Xyzabc123'

    ----------------------- demo -----------------------

String.prototype.toSnakeCase() 
--------------------------

#Type: toSnakeCase(): Boolean;
#Notes: replaces all spaces and punctuation in a given string with underscores;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.toSnakeCase();
        output ---> 'hi_my_name_is_xyzabc123'

    ----------------------- demo -----------------------    

String.prototype.toKebabCase() 
--------------------------

#Type: toKebabCase(): Boolean;
#Notes: replaces all spaces and punctation in a given string with hyphens;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.toKebabCase();
        output ---> 'hi-my-name-is-xyzabc123'

    ----------------------- demo -----------------------   
    
String.prototype.toTrainCase() 
--------------------------

#Type: toTrainCase(): Boolean;
#Notes: replaces all spaces and punctation in a given string with hyphens, and capitalizes the first letter of everyword;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.toTrainCase();
        output ---> 'Hi-My-Name-Is-Xyzabc123'

    ----------------------- demo -----------------------   

String.prototype.removeWhiteSpace() 
--------------------------

#Type: removeWhiteSpace(): String;
#Notes: removes all whitespace from a string;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.removeWhiteSpace();
        output ---> 'himynameisxyzabc123'

    ----------------------- demo -----------------------       
        
String.prototype.reverseWords() 
--------------------------

#Type: reverseWords(): String;
#Notes: reverses everyword in a string;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = 'hi my name is xyzabc123'

        str.reverseWords();
        output ---> 'ih ym eman si 321cbazyx'

    ----------------------- demo -----------------------     

String.prototype.escapeHTML() 
--------------------------

#Type: escapeHTML(): String;
#Notes: replaces any HTML tags in a string with their corresponding  HTML entities;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = '<div>hi<div>'

        str.escapeHTML();
        output ---> '&lt;div&gt;hi&lt;/div&gt'

    ----------------------- demo -----------------------     

String.prototype.unescapeHTML() 
--------------------------

#Type: unescapeHTML(): String;
#Notes: replaces any HTML entities in a string with its corresponding HTML tag;
#Mutates: false;

    ----------------------- demo -----------------------

        let str = '&lt;div&gt;hi&lt;/div&gt'

        str.unescapeHTML();
        output ---> '<div>hi<div>'

    ----------------------- demo -----------------------         
