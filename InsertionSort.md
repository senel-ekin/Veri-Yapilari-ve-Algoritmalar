## PROJE 1
### [22,27,16,2,18,6] -> Insertion Sort

#### 1) **Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
###### ***Dizideki elemanları tek tek inceleyerek, sırasıyla bir öncekinden küçük olan elemanın geriye atıldığı sıralama yöntemidir.***


##### ***22 verisi kendi başına sıralıdır ve hiçbir işlem gerekmez.***
|1. AŞAMA|[22,27,16,2,18,6]|    
|--------|-----------------|

##### ***27 verisi için karşılaştırmalıyız. 22, 27'den küçüktür. O halde bir işlem yapılmaz.***
|2. AŞAMA|[22,27,16,2,18,6]|    
|--------|-----------------|

##### ***16 sayısı için bakarsak eğer, hem 27'den hem 22'den küçüktür. Önce 27 ile sonra 22 ile yer değiştirir.***
|3. AŞAMA|[16,22,27,2,18,6]|    
|--------|-----------------|

##### ***2 ile 27 kıyaslanacaktır. 2, 27 sayısından küçüktür o halde yer değiştirilir. 2 yeni yerinde bir gerisinde olan 22 sayısından da küçüktür ve bundan dolayı 22 ile de yer değiştirir. 16 sayısından da küçük olan 2, 16 ile de yer değiştirerek geriye gitmiş olur.*** 
|4. AŞAMA|[2,16,22,27,18,6]|    
|--------|-----------------|

##### ***18 için de aynı kıyaslamalar yapılır ve kendinden büyük olan sayıların gerisine gider.***
|5. AŞAMA|[2,16,18,22,27,6]|    
|--------|-----------------|

##### ***Son olarak 6 sayısına bakarız. 6, 2'ye kadar olan gerisindeki sayılardan küçüktür. Böylece yer değiştire değiştire yani geriye gelerek 16 sayısının gerisine yerleşir.***
|6. AŞAMA|[2,6,16,18,22,27]|    
|--------|-----------------|

#### 2) **Big-O gösterimini yazınız.**
### O(n^2)

#### 3) **Time Complexity**
###### ***Worst Case: Aradığımız sayının sonda olması.***
##### n^2

###### ***Average case: Aradığımız sayının ortada olması.***
##### n^2

###### Best case: Aradığımız sayının dizinin en başında olması.
##### n

#### 4) **Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
##### Ortada olduğundan dolayı Avarage Case kapsamına girer.

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. Adım -> [7,3,5,8,2,9,4,15,6]
2. Adım -> [3,7,5,8,2,9,4,15,6]
3. Adım -> [3,5,7,8,2,9,4,15,6]
4. Adım -> [3,5,7,8,2,9,4,15,6]



