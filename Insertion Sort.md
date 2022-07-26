 ?) [22,27,16,2,18,6] -> Insertion Sort türüne göre yapılırsa;
	

[22,27,16,2,18,6] ->  Dizinin ikinci elemanı alınır ve ilk elemanla karşılaştırma işlemi yapılır.
[22,27,16,2,18,8] ->  2.eleman 27 seçildi, 22'den büyük olduğu için yer değiştirme yapılmadı.
[22,16,27,2,18,8] ->  3.eleman 16, 27'den küçük olduğu için yer değiştirme yapıldı.
[16,22,27,2,18,8] ->  16 22'den küçük olduğu için tekrar yer değiştirme yapıldı.
[16,22,2,27,18,8] ->  2 22'den küçük olduğu için yer değiştirme yapıldı.
[16,2,22,27,18,8] ->  2 değeri 16'dan küçüktür ve başa gelir.
[2,16,22,27,18,8] ->  18 27'den küçüktür yer değiştirme yapılır.
[2,16,22,18,27,8] ->  18 22'den küçüktür yer değiştirme yapılır.
[2,16,18,22,27,8] ->  18 16'dan büyüktür yer değiştirme yapılmaz.
[2,16,18,22,27,8] ->  8 27'den küçüktür yer değiştirme yapılır.
[2,16,18,22,8,27] ->  8 22'den küçüktür yer değiştirme yapılır.
[2,16,18,8,22,27] ->  8 18'den küçüktür yer değiştirme yapılır.
[2,16,8,18,22,27] ->  8 16'den küçüktür yer değiştirme yapılır.
[2,8,16,18,22,27] ->  8 2'den büyüktür yer değiştirme yapılmaz.
[2,8,16,18,22,27] ->  Dizinin sıralanmış son hali


 ?) Big-O gösterimini yazınız.

	Big-O: O(n^2)

Time Complexity: 
Average case-> Aradığımız sayının ortada olması
Worst case-> Aradığımız sayının sonda olması
Best case-> Aradığımız sayının dizinin en başında olması.

 ?) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2,8,16,18,22,27]
Average case kapsamına girer. Çünkü dizi sıralandıktan sonra 18 sayısı dizinin ortalarında olur.


 ?) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


[7,3,5,8,2,9,4,15,6] ->  Dizinin ikinci elemanı olan 3 seçilir ve 7'den küçük olduğu için yer değiştirme yapılır.
[3,7,5,8,2,9,4,15,6] ->  5 seçilir ve 7'den küçük olduğu için yer değiştirme yapılır.
[3,5,7,8,2,9,4,15,6] ->  5 3'den büyük olduğu için yer değiştirme yapılmaz.
[3,5,7,8,2,9,4,15,6] ->  4.eleman olan 8 seçilir ve karşılaştırma yapılır.

Son adımda  oluşan dizi [3,5,7,8,2,9,4,15,6] olur.



