Proje 2
[16,21,11,8,12,22] -> Merge Sort
Yukar�daki dizinin sort t�r�ne g�re a�amalar�n� yaz�n�z.
Big-O g�sterimini yaz�n�z.

Solution:

Step 1: [16,21,11,8,12,22] -> Merge Sort A�amalar�:

[16,21,11] [8,12,22]
[16,21] / [11] [8,12] / [22]
[16] - [21] / [11] [8] - [12] / [22]
[16,21] / [11] [8,12] / [22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22]

Step 2: Big-O -> O(nlogn)