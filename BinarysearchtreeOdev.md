## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
### Her gelen eleman rootumuza göre büyükse sağına,küçükse soluna geçecek şekilde yerleşecektir.


Root burada 7 dir.Aşağı katmanlara inildiğinde root devam ettiğimiz yönde bir sonraki eleman olacaktır.
5 sayısı 7 den küçük soluna gelecek.

|  | 7|  |
|- |- |- |
| 5|  |  |                            

1 sayısı 7'nin sonra 5'in soluna gelecek.

|  | 5|  |
| -|- |- |
| 1|  |  |


8 sayısı 7 nin sağına gelecek.

|  | 7|  |
|- |- |- |
| 5|  | 8|        

3 sayısı 7'nin soluna sonra 5'in soluna, sonra 1'in  sağına gelecek.

|  | 1|  |
| -|- |- |
|  |  | 3|


6 sayısı 7'nin soluna sonra 5'in sağına gelecek.

|  | 5|  |
| -|- |- |
| 1|  | 6|


0 sayısı 7'nin sonra 5'in sonra 1'in soluna gelecek.

|  | 1|  |
| -|- | -|
| 0|  |  |

9 sayısı 7'nin sağına sonra 8'in sağına gelecek.

|  | 8|  |
| -|- |- |
|  |  | 9|

4 sayısı 7'nin soluna sonra 5'in soluna sonra 1'in sağına sonra 3'ün sağına gelecek.

|  | 3|  |
| -|- | -|
|  |  | 4|

2 sayısı 7'nin soluna sonra 5'in soluna sonra 1'in sağına sonra 3'ün soluna gelecek.

|  | 4|  |
| -|- | -|
| 2|  |  |

## Son Halimiz

|  |  |  |  |  | 7|  |  |  |  |  |
| -|- |- |- |- |- |- |- |- |- |- |
|  |  |  |  |5 |  | 8|  |  |  |  |
|  |  |  |1 |  |6 |  | 9|  |  |  |
|  |  | 0|  |3 |  |  |  |  |  |  |
|  |  |  |2 |  | 4|  |  |  |  |  |
