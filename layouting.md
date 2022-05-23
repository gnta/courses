# CSS - Tata letak

Tata letak adalah bagaimana cara kita untuk menampilkan diposisi mana element pada html harus di tampilkan.

dalam mengatur tata letak pada css untuk setiap element, akan jauh lebih mudah bagi kita untuk memhaminya jika kita beranggapan bahwa setiap
element yang ada di dalam website kita terbagi menjadi sebuah kelompok kotak-kotak kecil.


## Anatomi

1. Sebuah kotak dapat memiliki banyak kotak" didalamnya
2. Kotak yang memiliki anak di sebut parent (induk)
3. Kotak yang berada didalam kotak lain di sebut child (anak)
4. Kotak parent (indux) memiliki kewenangan untuk Mengatur bagaimana anaknya harus berbaris
5. Sedangkan anaknya tidak dapat mengatur hal apapun untuk parent (induk) nya namun dapat melanggar aturan yang dibuat oleh parent (induk)nya untuk diri nya sendiri

## Mari kita mulai

dalam css untuk mengatur bagai mana anak berbaris kita bisa menggunakan property `display` yang bernilai `flex / grid`, namun dalam materi kali ini kita menggunakan flex sebagai media pembelajaran

```css 
.parent { display: flex / grid; }  
```

### Flex

pengertian tapi belum ketemu wkwk

#### Cara menggunakan

berikut adalah list property yang bisa digunakan untuk mengatur tata letak dengan flex

##### Parent

| No  | Property        | Value                                                               | description                                                                                   |
| --- | --------------- | ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| 1   | display         | flex                                                                | Untuk mendifinisikan bahwa element ini menggunakan flex untuk mengatur tata letak tampilannya |
| 2   | justify-content | center / flex-start (start) / flex-end (end) / space-between ...dll | Untuk mengatur bagaimana anaknya berbaris secara horizontal                                   |
| 3   | align-items     | center / flex-start / flex-end / stretch ...dll                     | Untuk mengatur bagaimana anaknya berbaris secara vertical                                     |
| 3   | gap             | px                                                                  | Untuk mengatur jarak diantara anak-anaknya                                                    |


