  1. will print prices.length, aka the latest value of 'i' after all loop iterations. var declares 'i' for global scope
  2. will print the most recent discountedPrice variable, aka the result if the given formula. var declares 'discountedPrice' for global scope, so its accessable
  3. will print the finalPrice variable, aka rounded to a while number discountedPrice. Its declared on the outside as well as with var keyword,it will get updated with latest value from inside the loop and output it in console
  4. returns list [50,100,200]
  5. error because 'i' is defined with 'let' within the scope of the for loop and doesn't extend beyond
  6. error because 'discountedprice' is defined with 'let' within the scope of the for loop and doesnt extent beyond
  7. will print the finalPrice variable, aka rounded to a while number discountedPrice. Its declared on the outside ,it will get updated with latest value from inside the loop and output it in console
  8. returns list [50,100,200]
  9. error because 'i' is defined with 'let' within the scope of the for loop and doesn't extend beyond
  10. error because 'discountedprice' is defined with 'const' within the scope of the for loop and doesnt extent beyond
  11. error because we are attempting to change the const, but if we ignore errors it will print 0 because finalPrice is declared as const and can not be changed
  12. error because we are attempting to change the value of const, but if we ignore errors it will return an empty list since discounted was declared with const and therefore can not be changed
  13. A. ```student.name ```  <br /> B. ```student.'Grad Year'```  <br /> C. ```student.greeting()```  <br /> D. ```student.'Favourite Teacher'.name```  <br /> E. ```student.courseLoad ``` 
  14. A. 32 as a string because it treated 2 as a string and appended it <br />
  B. 1 because with subtraction it treated string '3' as number and performed a normal math operation.<br />
  C. 3 as an number type. it tried adding null mathematically, which meant it would add nothing <br />
  D. 3null as a string. It treated null as a string that i was trying to append to 3. <br />
  E. 4, it treated true as a value of 1, converted to integer and performed math addition.<br />
  F. 0, it converted false as value of 0, casted it to integer and adding null did nothing to it<br />
  G. 3undefined, it treated undefined as a string and appended to a given string "3"<br />
  H. NaN. subtracting by default attempts to perform an arithmetic operation, but performing such operations with an undefined value causes NaN, aka not a number

15.  A. true because it treats numerical string as integer with a real integer and does a proper comparison<br />
B. false, in this case it arithmetically compares string "2" to the first char of string "12", which is "1", 2 < 12 is true, however 2 < 1 is false<br />
C. true, it will treat integer 2 as string as see them as equals<br />
D. false, they may have same value but different datatype and triple equals cares for the same type<br />
E. false, there is no way boolean true and integer 2 have anything in common<br />
F. true, function boolean() with convert a provided real parameter object into a true value
16. == compares values, even bypassing boundries between strings and integers, while === strictly requires values as well as given datatypes to be the same
17. 'How are you?' is printed. First condition is invalid because true needs to equate to 1, not 2, while else if statement will run because it doesn't have comparison, and a number on its own is interpreted as true, else statement never gets reached.
18. Answer in separate file
19. returns list [6, 8, 10]. newArr gets populated with modified values based on the callback function, for example first value is (1+2)*2. It wait for the addition to happen inside the callback function doSomething, then multiplies, then adds to the final list
20. Answer in separate file
21. 1,4,3,2 on separate lines one after another