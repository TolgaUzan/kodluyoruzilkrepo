# **Merge Sort Projesi  Odev 2**


---
## **Soru**

> [16,21,11,8,12,22] -> **Merge Sort**
> * 1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
> * 2.Big-O gösterimini yazınız.

## **Cevap**

> * -1.Sort türüne göre aşamaları ; 

```
*     [16,21,11,8,12,22]     *
1->    [16,21,11] [8,12,22]
2->  [16] [21,11] [8] [12,22]
3->[16] [21] [11] [8] [12] [22]
4->  [16] [11,21] [8] [12,22]
5->    [11,16,21] [8,12,22]
6->    [8,11,12,16,21,22]
```

> * -2.Big-O gösterimi - Big-O notation; 

```
> O(nlogn)
```


---
[Patika.com](https://app.patika.dev) 
**Author** [*Tolga Uzan*](https://app.patika.dev/tolgauzan)
---