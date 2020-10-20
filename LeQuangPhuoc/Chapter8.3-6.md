a Test thỏa mãn RACC:

* ```x < y``` true, ```x + y == 10``` true <br>
  twoPred(2, 8)
  
*  ```x < y``` false, ```x + y == 10``` true <br>
  twoPred(8, 2)
  
*  ```x < y``` true, ```x + y == 10``` false <br>
  twoPred(2, 7)
  
b Test thỏa mãn RICC:

*  ```x < y``` false, ```x + y == 10``` false <br>
  twoPred(8, 3)
  
*  ```x < y``` true, ```x + y == 10``` false <br>
  twoPred(2, 7)
  
*  ```x < y``` false, ```x + y == 10``` true <br>
  twoPred(8, 2)
