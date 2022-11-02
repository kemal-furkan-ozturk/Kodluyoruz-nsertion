# Kodluyoruz-nsertion

İnsertion Sort

[22,27,16,2,18,6] -> Insertion Sort

A.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Algoritma gereği önce en küçük sayı bulunacak ve birinci elemanla değiştirilecek 
daha sonra en küçük ikinci sayı bulunacak ve ikinci elemanla değişecek en sonunda 
tamamen küçükten büyüğe sıralanana dek

1-) [2,27,16,22,18,6] -> 2 ile 22  yer değiştirdi

2-) [2,6,16,22,18,27] -> 6 ile 27  yer değiştirdi

3-) [2,6,16,22,18,27]-> 16'nın yeri değişmedi

4-) [2,6,16,18,22,27]-> 18 ile 22  yer değiştirdi

5-) [2,6,16,18,22,27]-> 22'nin yeri değişmedi

6-) [2,6,16,18,22,27]-> 27'nin yeri değişmedi ve toplamda 6 işlem yapıldı 

B.Big-O gösterimini yazınız. 
n adet eleman için toplamda 1+2+3+....n adet işlem yapılacağı için 
1-) O(n^2)

C. Time Complexity:

Eğer aradığımız sayı dizinin ortalarındaysa Avarage case, eğer başlarındaysa Worst Case, eğer başlarındaysa Best Case

D.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizinin sıralanmış şekli = [2,6,16,18,22,27]

18 Sayısı dizinin ortasında olduğu için Avarage Case kapsamına girer.

E.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1-)[2,3,5,8,7,9,4,15,6] -> 2 ile 7  yer değiştirdi

2-)[2,3,4,8,7,9,5,15,6] -> 5 ile 4  yer değiştirdi

3-)[2,3,4,5,7,9,8,15,6] -> 8 ile 5  yer değiştirdi

4-)[2,3,4,5,6,9,8,15,7] -> 6 ile 7  yer değiştirdi
