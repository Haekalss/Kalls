![Disini menampikan sebuah microfrontend e-commerce sederhana](Gambar/Screenshot/Screenshot(29).png) 
Dengan menekan Button Sneakers, Loafers, Slip on, dan Boots
(Gambar/Screenshot/Screenshot(30).png)
Muncul perubahan paragraf menggunakan Javascript seperti gambar di atas
```
function paragraf1() {
  document.getElementById("sepatu").innerHTML =
    "Sneakers adalah sepatu yang biasanya dirancang untuk olahraga atau bentuk kegiatan fisik lainnya selain juga banyak dipakai untuk kegiatan sehari-hari. Sepatu kets mula-mula dipopulerisasikan oleh perusahaan-perusahaan seperti Converse, Nike, dan Spalding pada pertengahan abad ke-20.";
}
function paragraf2() {
  document.getElementById("sepatu").innerHTML =
    "Loafers merupakan sepatu slip on yang bisa digunakan untuk gaya formal, sporty, atau casual. Sepatu Loafers Pria biasanya tersedia dalam berbagai desain sehingga bisa dipilih sesuai selera.";
}
function paragraf3() {
  document.getElementById("sepatu").innerHTML =
    "Slip on adalah jenis sepatu dengan tampilan yang lebih minimalis tanpa adanya tali sebagai pengikat.";
}
function paragraf4() {
  document.getElementById("sepatu").innerHTML =
    "Sepatu bot adalah sejenis alas kaki. Mayoritas sepatu bot menutupi bagian telapak kaki sampai ke bagian mata kaki. Sebagian sepatu bot juga menutup bagian betis dan bahkan ada juga yang sampai ke pinggang. Pada zaman dahulu sepatu bot biasanya terbuat dari kulit dan karet.";
}
```
Selanjutnya dengan menekan button Home kembali lagi ke awal paragraf hilang
(Gambar/Screenshot/Screenshot(31).png)
```
function paragraf0() {
  document.getElementById("sepatu").innerHTML = "";
}```