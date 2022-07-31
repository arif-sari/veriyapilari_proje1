Proje 1.1
[22,27,16,2,18,6] -> Insertion Sort

Adım1- (n-1)
[2,27,16,22,18,6] 

Adım1- (n-2)
[2,6,16,22,18,27] 

Adım1- (n-3)
[2,6,16,18,22,27] 


--------------------------
Proje 1.2

Big O notation

n + (n-1) + (n-2) + (n-3) + ... + 1 = (n.(n+1))/2 =  n^2+n/2 

en büyük değer n^2 olduğu için big O notation değeri n^2 dir


------------------------

Proje 1.3

Worst Case: Aranan sayının sonda olması
[27,22,18,16,6,2]  

Best Case: Aranan sayının başta olması
[2,6,16,18,22,27] 

Average Case: Aranan sayının ortada olması
[2,6,16,18,22,27] 

----------------------------------

Proje 1.4


Dizi sıralandıktan sonra ortada kaldığı için avarage case kapsamına girecektir.


-----------------------------------

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]  Adım 1  (n-1)
[2,3,4,8,7,9,5,15,6]  Adım 1  (n-1)
[2,3,4,5,7,9,8,15,6]  Adım 1  (n-1)
[2,3,4,5,6,9,8,15,7]  Adım 1  (n-1)
