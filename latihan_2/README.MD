# Menggambar Pada Canvas

### ctx.lineWidth=10px

Digunakan untuk menentukan ketebalan dari suatu garis

### ctx.strokeRect(x,y,width,height)

Digunakan untuk membuat sebuah stroke atau garis untuk parameternya sama dengan ctx.fillRect()

### ctx.beginPath()

Adalah ntuk menandakan kita akan memulai menggambar sebuah gambar contohnya disini lingkaran

### ctx.stroke && ctx.fill / ctx.strokeStyle && ctx.fillStyle

Pada dasarnya sama saja akan tetapi perbedaanya jika stroke kita hanya menginginkan sebuah garis,akan tetapi beda dengan fill kita ingin menginginkan lebih dari sekedar garis

### ctx.arc()

Untuk menggambar sebuah lingkaran kita memerlukan method arc() ini,untuk parameternya sendiri ada
`(posisi X,posisi Y,Radius,startAngle,EndEngle/PI,arahJarumJam(True / False:default)`

Menggambar lingkaran dengan fungsi arc() dengan parameter yang ditentukan. Lingkaran digambar pada titik (95, 50) dengan ukuran jari-jari 40 piksel

Mulai digambar dari arah jam 3 (0 radian) menuju kembali ke arah jam 3 (2*π radian)

Untuk membuat sebuah lingkaran menjadi setengah kita bisa mengubahnya `Math.PI/1`,kita bisa melakukan modifikasi

![](https://github.com/RFaisal458/BelajarHtmlCanvas/blob/master/latihan_2/img/circle.gif)

### ctx.moveTo()

Di gunakan untuk melakukan titik awal dari sebuah garis yang akan kita gambar,untuk parameternya sendiri (x,y)

### ctx.lineTo()

Di gunakan untuk akhir dari garis,lineTo() sendiri adalah sambungan dari moveTo() sendiri untuk parameternya sendiri (x,y)

### ctx.closePath()

Di gunakan untuk menutup garis atau kita akan menyambungnya dengan titik awal,contoh gambar yang bisa di lihat

![example](https://github.com/RFaisal458/BelajarHtmlCanvas/blob/master/latihan_2/img/tanpa_closePath.png)


Untuk hasilnya sendiri bisa di lihat di bawah ini

![result](https://github.com/RFaisal458/BelajarHtmlCanvas/blob/master/latihan_2/img/hasil.png)
