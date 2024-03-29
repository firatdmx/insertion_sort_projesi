
**1)** **[22,27,16,2,18,6] -> Insertion Sort**

Dizideki en küçük sayı linear şekilde aranır ve bulunduğunda 0. indexteki eleman ile yerleri değiştirilir. İkinci en küçük sayı aranırken de linear aramaya 0.eleman yerine 1. elemandan başlanır ve süreç bu şekilde ilerler.

Soruda verilen [22,27,16,2,18,6] dizisinde en küçük sayı 2 olduğu için 2 bulunduğunda 22 sayısı ile yer değiştirir.

[22,27,16,2,18,6]

[2,27,16,22,18,6]

Bir sonraki en küçük sayı olan 6 sayısı bulunduğunda ise 1.indexteki 27 sayısı ile yer değiştirir.

[2,6,16,22,18,27]

Sonraki adımda 16 sayısı en küçük olduğu için yer değişikliği yapılmaz ve bir sonraki indexteki 22 sayısından aramaya başlanır ve kalan dizideki en küçük 18 sayısı bulunur. Bulunan 18 sayısı 22 ile yer değiştirir.

[2,6,16,22,18,27]

Bu işlem sonucunda [2,6,16,18,22,27] şeklindeki doğru dizilimli sonuca ulaşılır.

	İşlem adımları:

	I. [22,27,16,2,18,6]

	II. [2,27,16,22,18,6]

	III. [2,6,16,22,18,27]

	IV. [2,6,16,18,22,27]
****
**2)** **Big O Notation: O(n^2)**
****
**3) Time Complexity:**

	Average case: O(n^2)
	Best case: O(N)
	Worst case: O(n^2)
****
**4) 18 sayısı linear şekilde aranırken dizinin tam ortasında bulunduğundan “Average Case” kapsamına girer.**
****
**5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı**

	I. [7,3,5,8,2,9,4,15,6]

	II. [2,3,5,8,7,9,4,15,6]

	III. [2,3,5,8,7,9,4,15,6]

	IV. [2,3,4,8,7,9,5,15,6]
