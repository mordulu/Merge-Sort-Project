# Patika.dev Url
[https://app.patika.dev/mordulu](url)


# MERGE SORT PROJESİ

## Proje 2

[16,21,11,8,12,22] -> Merge Sort
-
+ Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
+Big-O gösterimini yazınız.

---

 [16,21,11,8,12,22] Merge Sort aşamaları;

              [16,21,11,8,12,22]
               /              \
        [16,21,11]           [8,12,22]  
           /    \              /    \
       [16,21] [11]          [8,12] [22] 
         /  \    \            /  \    \
       [16] [21] [11]       [8] [12] [22]
         \   /    /          \   /    /
        [16,21] [11]         [8,12] [22]
            \    /              \    /
         [11,16,21]           [8,12,22]
                 \             / 
                [8,11,12,16,21,22]




Big-O gösterimi

\
1.Step -> n

\
2.Step -> n/2

\
3.Step -> n/4

\
4.Step -> n/8

\
....

\
Step (n-1) -> (n-1)/2^(n-2)

Summary ->  n + n/2 + ... = n(1 + 1/2 + ...) = nlogn


O(nlogn)




