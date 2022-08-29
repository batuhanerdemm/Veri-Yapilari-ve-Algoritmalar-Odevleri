  
  [7,5,1,8,3,6,0,9,4,2] dizisinin Binary Search Tree aşamalarını yazınız.
  Root belirlendikten sonra Roottan küçük olanlar sola büyük olanlara sağa toplanır.
                             7
                            / 
                           5 
                    5 7 den küçüktür sola yazılır
                             7
                            /
                           5
                          /
                         1
                     1 sola yazılır.
                          
                             7
                            / \
                           5   8
                          /    
                         1      
                      8 7 den büyük olduğu için sağa yazıldı   
                             7
                            / \
                           5   8
                          / 
                         1   
                          \
                           3
                        7>3 1 in sağına yazıldı.
                             7
                            / \
                           5   8
                          / \
                         1   6
                          \ 
                           3 
                        7>6  5 in sağına yazıldı.
                             7
                            / \
                           5   8
                          / \   \
                         1   6   
                        / \ 
                       0   3 
                       7>0 0 solun en altına yazıldı.
                             7
                            / \
                           5   8
                          / \   \
                         1   6   9
                        / \ 
                       0   3 
                       9>7 olduğu için sağa yazıldı.
                             7
                            / \
                           5   8
                          / \   \
                         1   6   9
                        / \ 
                       0   3 
                            \
                             4
                       9>4 sola yazıldı daha sonra 3 ün sağına yazıldı.
                             7
                            / \
                           5   8
                          / \   \
                         1   6   9
                        / \ 
                       0   3 
                          / \
                         2   4
                         
                       Son olarak 2 yi ekledik 9>2   