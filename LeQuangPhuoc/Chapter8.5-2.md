Bao phủ CACC:

* Chuyển đổi trạng thái từ 1 -> 2:
* Vị từ:  Button2 ∧ (Gear = Park ∨ ignition = off )

|             |     Giá trị kiểm thử    |    P   | Đầu ra mong đợi  |
| ----------- | ---------| -------| ------------|
|      1      |     Button2 ∧ Gear = Park    |    T   |       2    |
|      2      |     Button1 ∧ Gear = Park      |    F   |       1     |
|      3      |    Button2 ∧ (Gear = Park ∧ ignition = on)     |    T   |       2     |
|      4      |     Button2 ∧ (Gear != Park ∧ ignition = on)      |    F   |       1     |
|      5      |     Button2 ∧ (Gear != Park ∧ ignition = off )      |    T   |       2     |
|      6      |     Button2 ∧ (Gear != Park ∧ ignition = on)      |    F   |       1     |

* Chuyển đổi trạng thái từ 1 -> 3:
* Vị từ:   sideMirrors ∧ ignition = on


|             |     Giá trị kiểm thử    |    P   | Đầu ra mong đợi  |
| ----------- | ---------| -------| ------------|
|      1      |     sideMirrors ∧ ignition = on    |    T   |       3    |
|      2      |     ignition = on      |    F   |       1     |
|      3      |     sideMirrors ∧ ignition = on     |    T   |       3    |
|      4      |     sideMirrors ∧ ignition = of      |    F   |       1     |

