# Patika-Binary-Search-Tree

* Patika Profil Linkim: https://app.patika.dev/guleerbilal

## Proje 3

* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    * Root 7'dir.

    * Aşama 1:

        * 5 < 7

                         7
                        /
                       5

    * Aşama 2:

        * 1 < 7 , 1 < 5

                         7
                        /
                       5
                      /
                     1

    * Aşama 3:

        * 8 > 7

                         7
                        / \
                       5   8
                      /
                     1

    * Aşama 4:

        * 3 < 7 , 3 < 5 , 3 > 1

                         7
                        / \
                       5   8
                      /
                     1
                      \
                       3

    * Aşama 5:

        * 6 < 7 , 6 > 5
        
                        7
                       / \
                      5   8
                     / \
                    1   6
                     \
                      3                           

    * Aşama 6:

        * 0 < 7 , 0 < 5 , 0 < 1
        
                         7
                        / \
                       5   8
                      / \
                     1   6
                    / \
                   0   3 

    * Aşama 7:

        * 9 > 7 , 9 > 8
        
                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3

    * Aşama 8:

        * 4 < 7 , 4 < 5 , 4 > 1 , 4 > 3 
        
                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3                            
                        \
                         4

    * Aşama 9:

        * 2 < 7 , 2 < 5 , 2 > 1 , 2 < 3        
        
                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3                            
                      / \
                     2   4     
