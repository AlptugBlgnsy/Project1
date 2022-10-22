# Project1 ###Patika.Dev_INSERTION_SORT_Project

www.patika.dev

###[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

###[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

###Çözümleme

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

###[22,27,16,2,18,6] Dizi içerisndeki en küçük sayının 2 olduğu belirlenmiştir.

###[2,27,16,22,18,6] 2 ve 22 için yer değişikliği yapılmıştır.

###[2,6,16,22,18,27] 6 ve 27 için yer değişikliği yapılmıştır.

###[2,6,16,18,22,27] 18 ve 22 için yer değişikliği yapılmıştır.

###[22,27,16,2,18,6] Elde edilen yeni dizi.

2.Big-O gösterimi

### n, (n-1) , (n-2),......n      n^2      O(n^2) 

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

###A)Average Case: O(n^2)

###B)Best Case: O(n)

###C)Worst Case: O(n^2)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

###18 Sayısı diznin ortasında yer aldığı için Average case olarak adlandırılır.

###[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] 2 en küçük değer olarak seçilir ve 2 ile 7 yer değişir.

[2,3,5,8,7,9,4,15,6] 4 ile 5 yer değişir.

[2,3,4,8,7,9,5,15,6] 5 ile 8 yer değişir.

[2,3,4,5,7,9,8,15,6] 6 ile 7 yer değişir.

[2,3,4,5,6,9,8,15,7].................
