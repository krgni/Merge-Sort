# Merge-Sort
[16, 21, 11, 8, 12, 22] - > Merge Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

aşama - > [16, 21, 11] ve [8, 12, 22] şeklinde iki adet diziye bölünür.
aşama - > Birinci dizi ve ikinci dizi kendi içinde iki adet diziye bölünür: [16, 21] , [11] ve **[8, 12] ** , [22] olmak üzere.
aşama -> Daha sonra ikinci kez parçalara ayırdığım bu diziler kendi içlerinde sıralanabilir:
​ [11, 16, 21] ve [8, 12, 22] olacak şekilde.

aşama -> Kendi içlerinde sıralamış olduğumuz dizileri ilk elemandan başlayıp acaba dizinin en küçük elemanı bu mudur şeklindeki soruyla sıralayıp, merge edebiliriz:

[8, 11, 12, 16, 21, 22] dizimizin son ve merge edilmiş halidir.

**Big-O gösterimini yapınız.**
Dizi her seferinde ikiye bölünerek elde edildiğinden logn kere bölünmüş olacak. Her dizi bölünmesi sonrası (n-1) kere sorgu yapılarak dizilim sağlandığından time complex değeri logn olacaktır.

Dizi toplamda logn kere bölündüğü için de; Big -O gösterimi şu şekilde olacaktır : **O(nlogn) **
