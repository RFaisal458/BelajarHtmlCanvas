# Setup HTML Canvas

### let canvas=document.getElementById('canvas')

Untuk mendapatkan tag canvas sendiri dengan javascript

### let ctx=canvas.getContext('2d')

ctx sendiri berarti adalah context,disini kita akan menggunakan 2dimensi,untuk sederhananya kita bisa anggap ctx sendiri sebagai pensil untuk menggambarnya

### canvas.width=canvas.scrollWidth && canvas.height=canvas.scrollHeight

Di gunakan agar ukuran element yang ada di dalam responsive terhadap wadah canvasnya,jika tidak menggunakannya kita akan mendapatkan hasil seperti ini

![](https://github.com/RFaisal458/BelajarHtmlCanvas/blob/master/latihan_1/tanpa_widthOrheight.png)

### ctx.fillStyle

Di gunakan untuk memberikan warna pada suatu element untuk isi nya sendiri kita bisa memberikan biasa atau hexa atau rgb

### ctx.fillRect && ctx.fillText

fillRect sendiri digunakan untuk membuat sebuah element dengan parameternya (posisi X,posisi Y,width,height) sedangkan untuk fillText sendiri di gunakan untuk membuat sebuah text akan tetapi sebelum mendefinisiakan fillText kita harus melakukan `ctx.font="30px Arial"`

Untuk Hasil Akhirnya bisa di lihat pada gambar ini

![Result](https://github.com/RFaisal48/BelajarHtmlCanvas/blob/master/latihan_1/img/hasil.png)




