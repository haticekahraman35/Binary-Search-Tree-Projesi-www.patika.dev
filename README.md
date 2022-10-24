# Binary-Search-Tree-Projesi-www.patika.dev
**www.patika.com > Veri Yapıları ve Algoritmalar > Binary Search Tree Projesi > Proje 3 kapsamında hazırlanmış proje çalışmasıdır.**

## Binary Search Tree Projesi
------------------------------

### 1. [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
------------------------------
``` 
1. Aşama: Root 7 seçilir. 5 sayısı 7 sayısından küçük olduğu için sol tarafa yazılır.
                                  7
                                /
                              5 
                              
```
2. Aşama: 1 sayısı 7 sayısından küçük olduğu için 7'nin soluna, 5 sayısından da küçük olduğu için 5'in soluna yazılır.

                                  7
                                /
                              5  
                            /
                          1 
                          
```
3. Aşama: 8 sayısı 7 sayısından büyük olduğu için sağ tarafa yazılır.

                                  7
                                /  \
                              5      8
                            /
                          1 
                                                 
```
4. Aşama: 3 sayısı 7 ve 5 sayısından küçük olduğu için sol tarafa, 1 sayısından büyük olduğu için de 1 sayısının sağ tarafına yazılır. 

                                  7
                                /  \
                              5      8
                            /   
                          1 
                            \
                              3
                              
                              
```
5. Aşama: 6 sayısı 7 sayısından küçük 5 sayısından büyük olduğu için 5 sayısının sağ tarafına yazılır.

                                  7
                                /  \
                              5      8
                            /   \
                          1       6
                            \
                              3
                              
                              
```
6.Aşama: 0 sayısı 7, 5 ve 1 sayılarından küçük olduğu için 1 sayısının soluna yazılır.

                                  7
                                /  \
                              5      8
                            /   \
                          1       6
                        /   \
                       0      3
                       
```
7. Aşama: 9 sayısı 7 ve 8 sayısından büyük olduğu için 8 sayısının sağına yazılır. 

                                  7
                                /  \
                              5      8
                            /   \      \
                          1       6       9
                        /    \
                      0        3
                      

```
8. Aşama: 4 sayısı 7 ve 5 sayısından küçük, 1 ve 3 sayısından büyük olduğu için 3 sayısının sağına yazılır. 

                                  7
                                /  \
                              5      8
                            /   \      \
                          1       6       9
                        /   \
                      0      3
                               \
                                 4
                                 
```       
9. Aşama: 2 sayısı 7 ve 5 sayısından küçük, 1 den büyük, 3 den küçük olduğu için 3 ün soluna yazılır. 

                                  7
                                /  \
                              5      8
                            /   \      \
                          1       6       9
                        /   \
                      0      3
                           /   \
                         2       4       
