# PROJE 3 - Binary Search Tree

## Soru 
[ 7,5,1,8,3,6,0,9,4,2 ] dizisinin Binary Search Tree aşamaları
***
* root 7 secilirse

  5 < 7'den küçüktür ve 5 - 7'nin solunda kalacaktır.
 
                  7          
                 /            1. ASAMA
                /
               5             
 ***              
 1 < 7 ve 1 < 5 olduğundan 1 - 5'in solunda kalacaktır.      
        
                  7          
                 /
                /
               5              2. ASAMA
              / 
             /
            1    
 ***           
  7 < 8  olduğundan 8 - 7'nin sagında kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8        3. ASAMA
              / 
             /
            1     
 ***           
 3 < 7 ve 3 < 5 ve 1 < 3 olduğundan 3 - 1'in sagında kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8      
              / 
             /                4. ASAMA
            1 
             \
              \
               3
***              
6 < 7 ve 5 < 6  olduğundan 6 - 5'in sagında kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8      
              / \ 
             /   \            5. ASAMA
            1     6
             \
              \
               3
***
0 < 7 ve 0 < 5 ve 0 < 1   olduğundan 0 - 1'in solunda kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8      
              / \ 
             /   \            6. ASAMA
            1     6    
           / \ 
          /   \            
         0     3      
***
7 < 9 ve 8 < 9   olduğundan 9 - 8'in sağında kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8      
              / \     \
             /   \     \      7. ASAMA
            1     6     9  
           / \ 
          /   \            
         0     3   
***
4 < 7 ve 4 < 5 ve 1 < 4 ve 3 < 4  olduğundan 4 - 3'un sağında kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8      
              / \     \
             /   \     \     8. ASAMA
            1     6     9  
           / \ 
          /   \            
         0     3
                \ 
                 \            
                  4   
***
2 < 7 ve 2 < 5 ve 1 < 2 ve 2 < 3  olduğundan 2 - 3'un solunda kalacaktır.      
        
                  7          
                 / \
                /   \
               5     8      
              / \     \
             /   \     \     9. ASAMA
            1     6     9  
           / \ 
          /   \            
         0     3
              / \ 
             /   \            
            2     4  
***

[Guzel bir patika](https://www.patika.dev/tr)