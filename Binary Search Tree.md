# Proje 3 - Binary Search Tree

## 1.Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Çözüm
Root  6 olarak seçilirse:

-> 8, 6'nın sağındadır.

-> 7, 6'nın sağındadır, 8'in solundadır.

-> 3, 6'nın solundadır.

-> 9, 6'nın sağındadır, 8'in sağındadır.

-> 4, 6'nın solundadır, 3'ün sağındadır.

-> 1, 6'nın solunda, 4'ün solundadır.

-> 5, 6'nın solunda, 4'ün sağındadır.

-> 2, 6'nın solunda, 3'ün solundadır.

-> 0, 6'nın solunda, 2'nin solundadır.