1. Number 3 will be the output. i is declared and incremted in the for loop at line 6. Since length of "prices" is 3, i, starting from 0, would be incremented 3 times before the condition "i < prices.length" determines that i is no longer less than length of "prices".

2. 150 will be the output. Line 7 declares and assignes "discountedPrice" with the "prices[i]" at a particular "i" times (1-discount). Since the last "prices[i]" is 300, it would calculate "discountedPrice" to be 150.
   
3. 150 will be the output. Since the last time "finalPrice" is assigned is when "discountedPrice" is 150, and that 150 is an integer, "finalPrice" will be 150 just like "discountedPrice".
   
4. A list of discounted prices will be returned [50, 100, 150]. This is because in each loop "finalPrice" is pushed into "discounted" list, and discounted is returned after the loop, so the list is returned.
   
5. There will be an error "Uncaught ReferenceError ReferenceError: i is not defined". Because a variable declared as "let" only exsists within the block which is the for loop at line 6 in this case. So "i" is not considered defined when trying to use it at line 12.
   
6. There will be an error "Uncaught ReferenceError ReferenceError: discountedPrice is not defined". Just like "i", "discountedPrice" is within the scope of the for loop, so not accessible outside when trying to use in at line 13.
   
7. Number 150 will be the output. This is because "finalPrice" is within the scope of the entire function, meaning that it can be acesss within it.
   
8. A list of discounted prices will be returned [50, 100, 150]. This is because in each loop "finalPrice" is pushed into "discounted" list, and discounted is returned after the loop, so the list is returned.
   
9.  There will be an error "Uncaught ReferenceError ReferenceError: i is not defined". Because a variable declared as "let" only exsists within the block which is the for loop at line 6 in this case. So "i" is not considered defined when trying to use it at line 11.
    
10. Number 3 will be the output. Because "length" is the length of the list "prices" which is 3.
    
11. A list of discounted prices will be returned [50, 100, 150]. This is because in each loop "finalPrice" is pushed into "discounted" list, and discounted is returned after the loop, so the list is returned.
    
12. Notations:
    A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];

13. Arithmetic:
    A. '32'. number 2 is converted into a string '2' so '3' and '2' are concatenated to become '32'.
    B. 1. string '3' is converted into a number 3, 3-2 = 1.
    C. 3. null is converted into number 0, so 3+0 = 3.
    D. '3null'. null is converted into a string, so '3' and 'null' are concatenated to become '3null'.
    E. 4. Boolean true is converted into a number 1, so 1+3 = 4.
    F. 0. Boolean false is converted into a number 0, so is null, so 0+0 = 0.
    G. '3undefined'. undefined is converted into a string 'undefined', so '3' and 'undefined' are concatenated to become '3undefined'.
    H. NaN. Because undefined is converted to NaN, 3-NaN is also NaN.

14. Comparison:
    A. true. string '2' is converted into number 2, and 2>1 is true.
    B. false. string '2' and string '12' are being compared, and since the first character '1' in '12' is smaller than '2', '12' is larger than '2'.
    C. true. string '2' is convereted to number 2, so 2==2 is true.
    D. false. === operation checks types, it would return false because 2 is a number and '2' is a string.
    E. false. Boolean true is converted into number 1, so 1==2 is true.
    F. true. Any non-zero number converted to Boolean is always true, so Boolean(2) is true, and true == true is true.

15. == compa    res the values after type conversion and === checks types before even attempting to convert, returning false as long as variables of two different types are being compared.

16. 