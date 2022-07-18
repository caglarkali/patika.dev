  #  Proje 2

**[16,21,11,8,12,22] -> Merge Sort**

* **Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**
* **Big-O gösterimini yazınız.**

------------------


*Başlangıçta dizimizi tek eleman kalana kadar ikiye bölüyoruz. Sonrasında karşılaştırma yöntemini kullanarak sıralayarak birleştiriyoruz*

```mermaid
graph TD;
    A[16,21,11,8,12,22]-->B[16,21,11];
    A-->C[8,12,22];
    B-->D[16,21];
    B--->E[11];
    C--->F[8];
    C-->G[12,22];
    D-->H[16];
    D-->I[21];
    G-->J[12];
    G-->K[22];
    H-->L[16,21];
    I-->L[16,21];
    E-->M[8,11];
    F-->M[8,11];
    J-->N[12,22];
    K-->N[12,22];
    L-->O[8,11,16,21];
    M-->O[8,11,16,21];
    O-->P[8,11,12,16,21,22];
    N-->P[8,11,12,16,21,22];
```

Big-O notation: O(n * log n)
