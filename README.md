# MergeSortProject
[16,21,11,8,12,22] -> Merge Sort


Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.


Big-O gösterimini yazınız.

## Merge Sort Aşamaları


Öncelikle sayı dizisi ikiye ayrılır.[16,21,11] ve [8,12,22]


Daha sonra elde edilen diziler tekrar ikiye bölünür.[16,21],[11],
[8.12] ve [22] şeklinde


Tek eleman kalmasını istediğimiz için bölme işlemine devam edilir [16],[21],[11] ve [8],[12],[22] haline gelmiş olur.


Daha sonra kendi aralarında sıralı bir şekilde gruplanırlar [11,16,21] ve [8,12,22] şekline gelirler.


Son adım olarak iki grup kendi aralarında gruplanır ve dizinin son hali elde edilmiş olur->[8,11,12,16,21,22]


## Big O Notation Gösterimi


Worst Case:O(n*logn)


Average Case:O(n*logn)


Best Case:O(n*logn)


 www.patika.dev
