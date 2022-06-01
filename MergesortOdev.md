# Merge Sort Ödevi

### Dizinin Bölünme Aşamaları

```
* 16,21,11,8,12,22
* 16,21,11           8,12,22
* 16,21   11      8,12   22
* 16  21  11      8  12  22
```

**Buradan sonrası birleşme yeri**

```
* 16  21  11      8  12  22
* 16,21   11      8,12   22
* 11,16,21        8,12,22
* 8,11,12,16,21,22
```

### Big-O Gösterimi

```
* Sürekli 2 yere bölerek ilerlediği için 2^x=n -> x=logn dir. n tane eleman olduğu için işlem n kere tekrar eder ve n*logn olur.
```
