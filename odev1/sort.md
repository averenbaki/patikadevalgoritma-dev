# odev1 insetion sort
[22,27,16,2,18,6] -> Insertion Sort Aşamaları

1- Dizinin birinci indexte yer alan 2.elemanı başlangıç elemanı olarak seçilir.
[27]

2- Daha sonra 27 ile 22 kıyas edilir. 22 < 27 olduğu için sıralama aynı şekilde kalır.
[22,27,16,2,18,6] - Son Durum

3- Dizinin üçüncü elemanı 16 kontrol edilir. 16 < 27,22 olduğu için dizinin en başına kaydırılır.
[16,22,27,2,18,6]

4- Dizinin dördüncü elemanı 2 kontrol edilir. 2 < 27,22,16 olduğu için dizinin en başına kaydırılır.
[2,16,22,27,18,6]

5- Dizinin beşinci elemanı 18 kontrol edilir. 18 < 27, 22 olduğu için dizinin üçüncü sırasına kaydırılır.
[2,16,18,22,27,6]

6- Dizinin son elemanı 6 kontrol edilir. 6 < 27 ,22 , 18 ,16 olduğu için dizinin ikinci sırasına kaydırılır.

7-Dizinin çalıştır komutunda çıkan hali 
[2,6,16,18,22,27]

-Big-O=(n^2)

- Time Complexity:Average Case

# soru2

- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

- 1 - [2,3,5,8,7,9,4,15,6]
- 2 - [2,3,4,8,7,9,5,15,6]
- 3 - [2,3,4,5,7,9,8,15,6]
- 4 - [2,3,4,5,6,9,8,15,7]