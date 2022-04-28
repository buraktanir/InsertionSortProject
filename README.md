# [22,27,16,2,18,6] -> Insertion Sort

## 1.Soru

[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]
        
[2,6,16,18,22,27]

## 2.Soru  
    
[22,27,16,2,18,6] n tane işlem gerekiyor.


[2,27,16,22,18,6] n-1 tane işlem gerekiyor. -> [2,6,16,22,18,27] n-2 tane işlem gerekiyor. -> ............. -> 1 tane işlem gerekiyor.


n'den 1'e kadar olan sayıların toplamı:

${n*(n+1)}/2$ = $(n^2 + n)/2$ = O($n^2$)   
    
BigO = O($n^2$)
## 3.Soru
    
[22,27,16,2,18,6]

Dizimizin sıralanmamış halini göz önünde bulundurursak;

**worst case 6**

**average case 16 ve 2** 

**best case 22** 
olacaktır.

## 4.Soru  
    

[2,6,16,18,22,27] dizimizin sıralanmış hali bu şekildedir.

18 sayısı dizinin ortasında bulunmasından ötürü **average case** kapsamına girmektedir.

#   [7,3,5,8,2,9,4,15,6] -> Insertion Sort'a göre ilk 4 adımını yaz.

## 1.Adım

[2,3,5,8,7,9,4,15,6]

## 2.Adım

[2,3,4,8,7,9,5,15,6]

## 3.Adım

[2,3,4,5,7,9,8,15,6]

## 4.Adım

[2,3,4,5,6,9,8,15,7]
