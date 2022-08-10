<!-- [22,27,16,2,18,6]  Insertion Sort -->

<!-- 1- Verilen dizinin sort türüne göre aşamalarını yazınız -->

22 kendi başına sıralıdır. İşlem yok.

1.Adım	22	27	16	2	18	6

22 ve 27 karşılaştırılır. 22, 27 küçük olduğundan bir değişiklik olmaz.

2.Adım	22	27	16	2	18	6

27 ile 16 karşılaştırılır. 16 27'den küçük olduğu için yer değiştirirler. Yer değişikliğinden sonra 16 ve 22 karşılaştırılır. Aynı şekilde 16 22'den küçük olduğu için yer değiştirirler.


3.adım	16	22	27	2	18	6

2 ile 27 karşılaştırılır. 2 27'den küçük olduğu için yer değiştirirler. 2 22 ile karşılaştırılır 2 küçük olduğu için yer değiştirirler. Aynı işlem 16 için uygulanır, 2 küçük olduğu için yer değiştirirler.

4.Adım	2	16	22	27	18	6

18<27 olduğu için yer değiştirirler. 18<22 olduğu için yer değiştirirler. 18>16 olduğu için değişiklik olmaz.

5.Adım	2	16	18	22	27	6

6<27 olduğu için yer değiştirirler. 6<22 olduğu için yer değiştirirler. 6<18 olduğu için yer değiştirirler. 6<16 olduğu için yer değiştirirler.

2 6 16 18 22 27

<!-- 1 End -->

<!-- 2 - Big O Gösterimini Yazınız -->

O(n^2)

<!-- Time Complexitiy -->

Worst Case: O(n^2)
Average Case: O(n^2)
Best Case: O(n)


<!-- 4 - Dizi Sıralandıktan Sonra 18 Sayısı Hangi Case Kapsamına Girer? -->

Ortada olduğu için Average Case

<!-- 5 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. -->

7   3   5   8   2   9   4   15  6
3   7   5   8   2   9   4   15  6
3   5   7   8   2   9   4   15  6
3   5   7   8   2   9   4   15  6