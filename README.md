# Binary-Search-Tree-Project

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

###### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

- Dizinin ilk elamanı root olarak kabul edilir. Root = 7. Her adımda gelen eleman kendisinden küçükse sol tarafına büyükse sağ tarafına yazılacak.

```
7
```

```
   7
 /
5
```
```    
    7
   /
  5
 /
1      
```     
```     
    7
   / \
  5   8
 /
1      
```     
```     
    7
   / \
  5   8
 / 
1  
 \
  3 
``` 
```
    7
   / \
  5   8
 / \
1   6
 \
  3
```
```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3

```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```

###### [patika.dev](https://patika.dev/)
