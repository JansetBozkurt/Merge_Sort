# Merge_Sort
##### Patika.dev'in Veri Yapıları ve Algoritmalar eğitiminin projesi.



### [16,21,11,8,12,22] -> Merge Sort
#### **1.Yukarıdaki diziniin sort türüne göre aşamalarını yazınız.**

    [16,21,11,8,12,22] ilk önce sayı dizisini ikiye böleriz.
      - [16,21,11]     [8,12,22]     
    Daha sonra böldüğümüz dizileri bir daha ikiye böleriz.
      - [16,21]   [11]   [8,12]   [22]
    Dizileri tek eleman olacak şekilde parçalarız.
      - [16] [21] [11] [8] [12] [22]
    Her diziyi kendi içinde sıralamaya başlarız.  
      - [16]  [11,21]  [8,12]  [22] 
    Şimdi ise ikili olarak sıraya uygun bir şekilde diziler birleştirilir.
      - [11,16,21]  [8,12,22,]
    Elde edilen diziler uygun bir şekilde bir kez daha birleştirilir.
      - [8,11,12,16,21,22]
    Ve dizi sıralı hale gelir.
 
#### **2.Big O gösterimini yazınız.**
    Worst case   : O(n*logn)
    Average case : O(n*logn)
    Best case    : O(n*logn)
    
    
