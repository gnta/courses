# Display, Dimensi, Overflow, Margin, Padding


## Display

Property display pada css mengatur perilaku dari kotak tersebut.

| Syntax | Description                                                                                  |
| ------ | -------------------------------------------------------------------------------------------- |
| inline | Lebar kontennya sesuai dengan isi konentent, dan kita tidak dapat mengatur lebar / tingginya |
| block  | Lebar kontentnya dapat kita sesuaikan dengan keinginan kita                                  |


## Dimensi

Dimensi adalah ukuran yang kita berikan kepada sebuah element html dengan satuan tertentu

Dimensi digunakan untuk mengatur berapa besar element pada suatu halaman, atau berapa jarak yang ada di antara element

| Syntax       | Description                                            |
| ------------ | ------------------------------------------------------ |
| px           | pixel                                                  |
| %  (percent) | relatif kepada ukuran elemen parent / induk elementnya |
| em           | relatif kepada ukuran font size pada element           |
| rem          | relatif kepada ukuran font size pada root element      |

[Lihat lebih lengkap](https://www.w3schools.com/cssref/css_units.asp)


## Overflow

akan mengatur apakah konten akan dipotong atau menambahkan scrollbar saat elemen konten terlalu besar untuk muat di area yang telah ditentukan
[sumber](https://dosenit.com/css/overflow-di-css#:~:text=Overflow%20pada%20CSS-,CSS%20Overflow,di%20area%20yang%20telah%20ditentukan.)


| Syntax            | Description                                                                                             |
| ----------------- | ------------------------------------------------------------------------------------------------------- |
| visible (default) | konten tidak akan dipotong jika isinya melebihi ukuran yang di tentukan                                 |
| hidden            | Konten akan dipotong jika isinya melibihi ukuran yang di tentukan  dan kita tidak dapat melihat sisanya |
| scroll            | Kontent akan dipotong dan akan menambahkan scrollbar untuk melihat sisanya                              |
| auto              | Mirip seperti scroll hanya dia akan menambahkan scrollbar jika dibutuhkan                               |

[Sumber dan lihat lebih lengkap](https://www.w3schools.com/css/css_overflow.asp)


### Overflow-x dan overflow-y

secara default overflow mengatur content secara horizontal (kesamping) dan vertical (kebawah) secara bersamaan.
namun jika kita menginginkan untuk mengatur horizontal / vertikal saja kita dapat menggunakan :

| Syntax     | Description                                          |
| ---------- | ---------------------------------------------------- |
| overflow   | Untuk mengatur konten secara vertikal dan horizontal |
| overflow-x | Untuk mengatur konten secara horizontal              |
| overflow-y | Untuk mengatur konten secara vertikal                |

## Margin

Area transparant diluar element yang dapat kita gunakan untuk memberi jarak disekeliling antar element

## Padding

Area transparant didalam element yang bisa memberikan ruang (jarak) untuk konten didalam element