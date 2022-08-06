# Veri-Yapilari-Odev-1
## Insertion Sort Algoritması
### [22 , 27 , 16 , 2 , 18 , 6 ] Dizisinin Insertion Sort türüne göre aşamaları;
[2,27,16,22,18,6] (n işlem yapılır) <br>
[2,6,16,22,18,27] (n-1 işlem yapılır) <br>
[2,6,16,22,18,27] (n-2 işlem yapılır) <br>
[2,6,16,18,22,27] (n-3 işlem yapılır) <br>
[2,6,16,18,22,27] (1 işlem yapılır) <br>
### Big o notation 
n + (n-1) + (n-2) + (n-3) + 1 (Toplam Formülü) = n . (n+1) /2 = n <sup>2</sup> + n /2 <br>
Big o(n <sup>2</sup>)'dir. <br>
Worst Case : O(n<sup>2</sup>) <br>
Average Case: O(n<sup>2</sup>) <br>
Best Case: O(n) <br>

### Time Complexity

Aradığımız sayı 6 olsun. Bu senaryoda; <br>
Worst Case: [22,27,16,2,18,6] <br>
Big O(n<sup>2</sup>) <br>
Average Case : [22,27,6,16,2,8] <br>
Big O(n) <br>
Best Case : [6,22,27,16,2,8] <br>
Big O(n) <br>

18 sayısı Average Case'dir. <br>

### [7 , 3 , 5 , 8 , 2 , 9 , 4 , 15 , 6] Dizisinin Insertion Sort'a göre ilk 4 adımı. 
1-) [2,3,5,8,7,9,4,15,6] <br>
2-) [2,3,5,8,7,9,4,15,6] <br>
3-) [2,3,4,8,7,9,5,15,6] <br>
4-) [2,3,4,5,7,9,8,15,6] <br>
