# Veri-Analizi-Patikası
https://app.patika.dev/
Patika.dev - Insertion Sort Projesi

# Insertion Sort Projesi

**[22,27,16,2,18,6] - Insertion Sort**

֎ 1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

֎ 2-Big-O gösterimini yazınız.

֎ 3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

֎ 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

֎ 5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**Insertion Sort Aşamaları**

[22,27,16,2,18,6] - (m)

[2|,27,16,22,18,6] - (m-1)

[2,6|,16,22,18,27] - (m-2)

[2,6,16|,18,22,27] - (m-3)

**Big O Notation Gösterimi**


Worst Case: O(m²) = m+(m-1)+(m-2)....+1

Average Case: O(m²)

Best Case: O(m)

**Time Complexity**

Worst Case: [27,22,18,16,6,2]

Best Case: [2,6,16,18,22,27]

**18 Sayısının Case Durumu**

Dizimiz küçükten büyüğe yapıldığında [2,6,16,18,22,27] şeklini alır ve 18 sayısı bu dizinin ortanca değeridir. Bu yüzden average case diyebiliriz.

[7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]
