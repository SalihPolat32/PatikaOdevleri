# PatikaOdevleri

[16,21,11,8,12,22] -> Merge Sort

1.
              Soru 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
                                
              n0:               [16,21,11,8,12,22]
                                  /            \
              n1:            [16,21,11]     [8,12,22]
                              /    /           \    \
              n2:          [16] [21,11]      [8,12]  [22]
                            /     /  \        /  \      \
              n3:         [16]  [21] [11]   [8] [12]    [22]
                           |      \   /      \   /       |
              n4:         [16]   [11,21]     [8,12]     [22]
                            \      /           \         /
              n5:          [11,16,21]           [8,12,22]
                                \                  /
              n6:                [8,11,12,16,21,22]  
  2.

              Soru 2)Big-O gösterimini yazınız.
              
              n = 2^x
              x = logn ise O(nlogn)
