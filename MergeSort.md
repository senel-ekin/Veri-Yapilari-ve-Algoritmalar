## PROJE 2

### [16,21,11,8,12,22] -> Merge Sort
###### ***Bir listeyi tek eleman kalana kadar her adımda ortadan parçaya bölerek devam eder ve sıralar.***

|  |  |  |16|21|11|8 |12|22|  |  |  |
|--|--|--|--|--|--|--|--|--|--|--|--|
|  |  |16|21|11|  |  |8 |12|22|  |  |
|  |16|21|  |11|  |  |8 |12|  |22|  |
|16|  |21|  |11|  |  |8 |  |12|  |22|
|  |16|21|  |11|  |  |8 |12|  |22|  |
|  |  |11|16|21|  |  |8 |12|22|  |  |
|  |  |  |8 |11|12|16|21|22|  |  |  |

### Big-O gösterimi
#### O(n*(logn)) 
#### n = 6  ***_olduğundan dolayı yerine yazarsak eğer yukarıdaki listemize uygun Big-O gösterimi_***
#### O(6*(log6))  ***_şeklindedir._***
