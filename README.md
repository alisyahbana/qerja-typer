Typer Problem   
    
Kita mencari developer yang mandiri, ketika ada masalah, aktif mencari solusi dengan sendirinya dan mudah mengerti instruksi tanpa terlalu banyak menanyakan untuk memahami instruksi.     
Berikut adalah aplikasi Javascript yang simple.    
Kami tidak akan menjelaskan bagaimana cara kerjanya atau library apa yang dipakai.   
    
Pertanyaan:   
1. Sebutkan library apa saja yang dipakai, website library itu dimana, dan dokumentasi library itu ada dimana.    
2. Aplikasi itu 'laggy'. Kenapa? Bagaimana cara membuat animasi lebih 'smooth'?    
3. Aplikasi itu tidak akan jalan di salah satu 3 browser populer (Chrome, Firefox, Internet Explorer)? Kenapa? Solusinya hanya menghapus satu character di code, character yang mana?    
4. Implementasikan tombol Start, Stop, Pause, dan Resume.   
5. Ketika ukuran window dirubah, susunan huruf yang 'terbentur' batas window menjadi tidak 1 baris. Benarkan.    
6. Implementasikan sistem score.   
7. Implementasikan hukuman berupa pengurangan nilai bila salah ketik.

1.daftar library yang digunakan :

a. Jquery -> https://jquery.com/, dokumentasi bisa di cek di http://api.jquery.com/

b. Jquery UI -> http://jqueryui.com, dokumentasi bisa di cek di http://api.jqueryui.com/

c. underscoreJs -> http://underscorejs.org/, dokumentasi bisa dicek juga di http://underscorejs.org/

d. backboneJs -> http://backbonejs.org/, dokumentasi bisa dicek juga di http://backbonejs.org/

e. bootstrap -> https://getbootstrap.com/, dokumentasi bisa dicek di https://getbootstrap.com/docs/4.0/getting-started/introduction/

2. untuk membuat lebih smooth bisa merubah settingan di typer.js pada line 152 (var animation_delay). Jika di set makin rendah maka animasi akan lebih 'smooth'.

3. Dikarenakan saya develop menggunakan OSX jadi saya tidak menemukan masalah dari browser yang saya gunakan (chrome, firefox, safari)

untuk jawaban 4-7 bisa di cek di program