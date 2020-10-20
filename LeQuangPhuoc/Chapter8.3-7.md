|             |     a    |    b   |    c  | a v  b v c  |
| ----------- | ---------| -------| ------| ------------|
|      1      |     T    |    T   |    T  |       T     |
|      2      |     T    |    T   |    F  |       T     |
|      3      |     T    |    F   |    T  |       T     |
|      4      |     T    |    F   |    F  |       T     |
|      5      |     F    |    T   |    T  |       T     |
|      6      |     F    |    T   |    T  |       F     |
|      7      |     F    |    F   |    T  |       F     |
|      8      |     F    |    F   |    F  |       F     |


a Tập kiểm thử thỏa GACC cho mảnh P:

* T = {(T, F, F),(F, T, F),(F, F, T),(F, F, F)}

b 

* Tập kiểm thử T có thỏa mãn bao phủ cạnh với mảnh Q

c Tập kiểm thử thỏa mãn bao phủ cạnh trên mảnh Q:

* T1 = {(T, T, T), (F, T, T), (F, F, T), (F, F, F)}
* T2 = {(T, T, F), (F, T, T), (F, F, T), (F, F, F)}
* T3 = {(T, F, T), (F, T, T), (F, F, T), (F, F, F)}
* T4 = {(T, F, F), (F, T, T), (F, F, T), (F, F, F)} 
* T5 = {(T, T, T), (F, T, F), (F, F, T), (F, F, F)} 
* T6 = {(T, T, F), (F, T, F), (F, F, T), (F, F, F)} 
* T7 = {(T, F, T), (F, T, F), (F, F, T), (F, F, F)} 
* T8 = {(T, F, F), (F, T, F), (F, F, T), (F, F, F)}
