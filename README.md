# Veri Yapıları ve Algoritmalar Modülü Insertion Sort Projesi 
This is a project for Patika.dev's Veri Yapıları ve Algoritmalar Module


# [22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

'''
1.adım = [22,27/16,2,18,6]  
2.adım = [16,22,27/2,18,6]  
3.adım = [2,16,22,27/18,6]  
4.adım = [2,16,18,22,27/6]  
5.adım = [2,6,16,18,22,27]
'''

2.Big-O gösterimini yazınız.

'''
O(n^2)
'''

3.Time Complexity: 
  Average case: Aradığımız sayının ortada olması
  Worst case: Aradığımız sayının sonda olması
  Best case: Aradığımız sayının dizinin en başında olması.
  
'''
Average case: O(n^2)  
Worst case: O(n^2)  
Best case: O(n)
'''

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

'''
18 sayısı 4. adımda sıralanmaktadır bu sebeple ne en iyi ne de en kötü durumda yer alacaktır. Bu sebeple Avarage Case kapsamına girmektedir.
'''

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

'''
1.adım = [3,7/5,8,2,9,4,15,6]  
2.adım = [3,5,7/8,2,9,4,15,6]  
3.adım = [3,5,7,8/2,9,4,15,6]  
4.adım = [2,3,5,7,8/9,4,15,6]
'''

