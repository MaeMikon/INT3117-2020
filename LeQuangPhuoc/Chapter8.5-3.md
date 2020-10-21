Bao phủ GICC:

* Chuyển đổi trạng thái từ 1 -> 2
* Vị từ: Button2 ∧ (Gear = Park ∨ ignition = off )

|             |     Giá trị kiểm thử    |    P   | Đầu ra mong đợi  |
| ----------- | ---------| -------| ------------|
|      1      |     Button2 ∧ (Gear != Park ∧ ignition = on)   |    T   |       Không khả thi     |
|      2      |     Button1 ∧ (Gear != Park ∧ ignition = on)    |    T   |       Không khả thi     |
|      3      |     Button2 ∧ (Gear != Park ∧ ignition = on)    |    F   |       1     |
|      4      |     Button1 ∧ (Gear != Park ∧ ignition = on)    |    F   |       1     |
|      5      |     Button2 ∧ (Gear = Park ∧ ignition = on)    |    T   |       2     |
|      6      |     Button2 ∧ (Gear != Park ∧ ignition = off )    |    T   |       2     |
|      7      |     Button1 ∧ (Gear = Park ∧ ignition = on)    |    F   |       1     |
|      8      |     Button1 ∧ (Gear != Park ∧ ignition = on)    |    F   |       1     |
|      9      |      Botton2 ∧ (Gear = Park ∧ ignition = on)   |    T  |       2    |
|      10      |     Button2 ∧ (Gear = Park ∧ ignition = off )    |    T   |       2    |
|      11      |     Button1 ∧ (Gear = Park ∧ ignition = on)     |    F   |       1     |
|      12      |    Button1 ∧ (Gear = Park ∧ ignition = off )    |    F   |       1     |

* Chuyển đôỉ trạng thái từ 1 -> 3
* Vị từ:  sideMirrors ∧ ignition = on

|             |     Giá trị kiểm thử    |    P   | Đầu ra mong đợi  |
| ----------- | ---------| -------| ------------|
|      1      |     sideMirrors ∧ ignition = off    |    T   |       Không khả thi    |
|      2      |     ignition = of     |    T   |       Không khả thi     |
|      3      |     sideMirrors ∧ ignition = off     |    F   |       1     |
|      4      |     ignition = off      |    F   |       1     |
|      5      |     ignition = on     |    T   |       Không khả thi     |
|      6     |     ignition = off     |    T   |       Không khả thi     |
|      7     |     ignition = on     |    F   |       1     |
|      8     |     ignition = off     |    F   |       1     |
