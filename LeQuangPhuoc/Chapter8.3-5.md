a Chuyển thành phương thức ```checkItExpand()``` :
```java
public static void checkItExpand (boolean a, boolean b, boolean c)
  {
    if (a)
      {
        if (b)
          {
            System.out.println ("1: P is true");
          }
        else if (c)
          { 
            System.out.println ("2: P is true");
          }
        else
          { 
            System.out.println ("3: P isn’t true");
          }
      }
    else
      { 
        System.out.println ("4: P isn’t true");
      }
  }
```

b 
|             |     a    |    b   |    c  | a && (b||c) |
| ----------- | ---------| -------| ------| ------------|
|      1      |     T    |    T   |    T  |       T     |
|      2      |     T    |    T   |    F  |       T     |
|      3      |     T    |    F   |    T  |       T     |
|      4      |     T    |    F   |    F  |       F     |
|      5      |     F    |    T   |    T  |       F     |
|      6      |     F    |    T   |    F  |       F     |
|      7      |     F    |    F   |    T  |       F     |
|      8      |     F    |    F   |    F  |       F     |

* GACC cho tập T1 cần phải có {2, 3, 4} và 1 trong {5, 6, 7}
* Tập T2: {1, 3, 4, 8}




