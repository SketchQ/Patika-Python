# Projeler

## Inserion Sort (Proje 1)

**[22,27,16,2,18,6]** -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```text
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] -- > [2,27,16,22,18,6] --> [2,6,16,22,18,27] -- > [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.

3 aşama olduğu için (n) , (n-1) , (1) şeklinde bulunur. Yani Big O Notation , O(n^2) şeklinde bulunur.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- Avarage Case : O(n^2)

- Worst Case : O(n^2)

- Best Case : O(n)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Avarage Case

```

```text

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] -- > 1. Aşama
[2,3,4,8,7,9,5,15,6] -- > 2. Aşama
[2,3,4,5,7,9,8,15,6] -- > 3. Aşama
[2,3,4,5,6,9,8,15,7] -- > 4. Aşama

```
