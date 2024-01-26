[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

CEVAP

1. 7 rakamını Kök(Root Node) olarak alalım.
2. İkinci rakam olan 5, 7'den küçük olduğundan 7 rakamının solundan köke bağlansın.
3. Ardından 1 rakamı, kök olan 7'den küçük olduğu için sol taraftan ilerlenir. Soldaki 5 rakamından da küçük olduğu için 5 rakamının soluna bağlanır. Yani 1'in parent'ı 5 olur.
4. Dördüncü eleman olan 8, kök olan 7'den büyük olduğu için 7'nin sağındadır. (8 > 7).
5. 3 rakamı, 7'den küçük, 7'nin solundaki 5'ten küçük ve 5'in solundaki 1'den büyük olduğu için 1'in sağından 1'e bağlanır. 1(parent) (1 < 3)
6. Altıncı eleman olan 6, kök olan 7'nin solundadır. 7'nin solunda, 5'in sağındadır.
7. Ardından 0 rakamı, 7'nin solunda, 5'in solunda ve 1'in solunda olacaktır.
8. Sekizinci eleman olan 9, kök olan 7'nin sağındadır (9 > 7) ve 8'in sağındadır (9 > 8)
9. Devamındaki 4 rakamı, 7'nin solunda -> 5'in solunda -> 1'in sağında -> 3'ün sağında yer alır.
10. Sonuncu eleman olan 2 rakamı, kök olan 7'nin solunda -> 5'in solunda -> 1'in sağında -> 3'ün solunda yer alır.

       7
      / \
     5   8
    / \   \
   1   6   9
  / \     
 0   3   
    / \
   2   4