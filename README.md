# Binary-Tree-Search

Patika.dev Profil --> https://app.patika.dev/seymackc

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* root:7
                  7
        
* 5: 7'nin soluna;   

                  7
            5            

 
* 1: 7'nin soluna, 5'in soluna; 

                  7
            5            
       1        

* 8: 7'nin sağına;   

                  7
            5           8
       1                  

       
* 3: 7'nin soluna, 5'in soluna, 1'in sağına;   


                  7
            5           8
       1                    
          3

* 6: 7'nin soluna, 5'in sağına;   


                  7
            5           8
       1        6            
          3

* 0: 7'nin soluna, 5'in soluna, 1'in soluna;   


                  7
            5           8
       1        6            
   0      3

* 9: 7'nin sağına, 8'in sağına;   


                  7
            5           8
       1        6            9            
   0      3

* 4: 7'nin soluna, 5'in soluna, 1'in sağına, 3'ün sağına;    


                  7
            5           8
       1        6            9
   0      3
            4

* 2: 7'nin soluna, 5'in soluna, 1'in sağına, 3'ün soluna;   


                  7
            5           8
       1        6            9
   0      3
        2   4
