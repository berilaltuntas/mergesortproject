# Data Structures Proje 2
-----

## Kodluyoruz Eğitimi Data Structures Ödevi 2


### Proje 2
---


**[16,21,11,8,12,22]** -> Merge Sort

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**
**Big-O gösterimini yazınız.**

---
### Yanıtlar
---


**[16,21,11,8,12,22]** -> Merge Sort

Merge Sorta göre aşamaları;

 1. aşama: **[16,21,11] [8,12,22]**


 2. aşama: **[16][21,11][8,12][22]**


 3. aşama: **[16][21][11][8][12][22]**


 4. aşama: **[16][11,21][8,12][22]**


 5. aşama: **[11,16,21] [8,12,22]**

6. aşama: **[8,11,12,16,21,22]**

---

Big O gösterimi: **O(nlogn)**