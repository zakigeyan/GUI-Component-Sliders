# GUI Component - Sliders

![Sliders](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/sliders.png?raw=true)

## Definisi

Sliders atau *track bar* adalah elemen kontrol grafis dimana pengguna dapat menetapkan nilai dengan menggerakkan indikator, biasanya secara horizontal. Dalam beberapa kasus, pengguna juga dapat mengklik pada suatu titik pada Sliders untuk mengubah pengaturan.

## Penggunaan

![Penggunaan](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/penggunaan.png?raw=true)

Sliders mencerminkan rentang nilai di sepanjang *bar*, dimana pengguna dapat memilih suatu nilai. Sliders sangat cocok untuk menyesuaikan pengaturan seperti rentang harga pada aplikasi toko online, *volume*, kecerahan, atau menerapkan filter pada suatu gambar.

## Prinsip

Sliders memiliki tiga prinsip.

1. Adjustable

![Adjustable](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/prinsip1.png?raw=true)

Sliders hanya boleh digunakan untuk memilih pilihan dari range  nilai yang telah ditetapkan.

2. Immediate

![Immediate](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/prinsip2.png?raw=true)

Sliders harus merepresentasikan secara real-time ketika pengguna berinteraksi dengan Sliders.

3. Accessible

![Accessible](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/prinsip3.png?raw=true)

Sliders harus menyediakan berbagai pilihan lengkap dalam range yang tersedia bagi pengguna untuk dipilih.

## Tipe

Sliders memiliki dua tipe.

- Continuous sliders

![Continuous](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/tipe1.png?raw=true)

Continous sliders memungkinkan pengguna memilih nilai sepanjang rentang subyektif.

- Discrete sliders

![Discrete](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/tipe2.png?raw=true)

Discrete sliders dapat disesuaikan dengan nilai tertentu dengan merujuk pada indikator nilainya.

## Anatomi

![Anatomi](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/anatomi.png?raw=true)

Sliders dapat berisi elemen-elemen berikut.

1. Track

Track menunjukkan rentang yang tersedia untuk pemilihan pengguna. Untuk jenis kiri-ke-kanan (LTR), nilai terkecil muncul di paling kiri, dan nilai terbesar di paling kanan. Untuk jenis kanan-ke-kiri (RTL) orientasi ini terbalik, dengan nilai terkecil di paling kanan dan nilai terbesar di paling kiri.

2. Thumb

Thumb meluncur di sepanjang range lintasan, menampilkan nilai yang dipilih melalui posisinya.

3. Value label (optional)

Value label menampilkan nilai numerik khusus yang dipilih saat ini.

4. Tick mark (optional)

Tick mark mewakili nilai yang telah ditentukan yang dapat digunakan oleh pengguna untuk memindahkan slider.

## Behavior

Continuous slider
-----------------

- Click and drag

Continuous slider ini dikontrol dengan mengeklik thumb dan menyeretnya.

- Click jump

Continuous slider ini dikontrol dengan mengeklik lintasan.

- Click and arrow

Continuous slider ini dikontrol dengan mengeklik thumb, lalu menggunakan arrow untuk memindahkannya.

- Tab and arrow

Continuous slider ini dikontrol dengan menggunakan tombol tab untuk memilih thumb slider yang diinginkan, kemudian menggunakan arrow untuk memindahkannya.

Discrete slider
---------------

- Click and drag

Discrete slider ini dikontrol dengan mengeklik thumb dan menyeretnya.

- Click jump

Discrete slider ini dikontrol dengan mengeklik lintasan.

- Click and arrow

Discrete slider ini dikontrol dengan mengeklik thumb, lalu menggunakan arrow untuk memindahkannya.

- Tab and arrow

Discrete slider ini dikontrol dengan menggunakan tombol tab untuk memilih thumb slider yang diinginkan, kemudian menggunakan arrow untuk memindahkannya.

- Tick marks (optional)

Discrete slider dapat menggunakan tanda centang yang berjarak sama di sepanjang track slider, dan thumb akan snap ke mereka. Setiap tanda centang harus mengubah pengaturan secara bertahap yang dapat dilihat oleh pengguna.

- Value entry field (optional)

Value entry field dapat diedit setelah memilih bidang thumb atau entri. Setelah entri teks dibuat, posisi slider secara otomatis diperbarui untuk mencerminkan nilai baru.

## Spesifikasi

Continuous sliders
------------------

![Continuous](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/spec1.png?raw=true)

Discrete sliders
----------------

![Discrete](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/spec2.png?raw=true)

## Implementasi Sliders

Untuk implementasi slider, saya mengambil contoh sliders dari aplikasi JD.id, salah satu e-commerce besar di Indonesia.

![Screenshot-1](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/Screenshot_20181113-224650.png?raw=true)

![Screenshot-2](https://github.com/zakigeyan/GUI-Component-Sliders/blob/master/Screenshot_20181113-224702.png?raw=true)

Sliders terdapat pada filter penentuan range harga yang diinginkan oleh calon pembeli. Pengguna cukup menggeser thumb yang ada pada slider untuk menentukan batas bawah dan batas atas range harga yang diinginkan.

## Referensi

- Material.io: https://material.io/design/components/sliders.html
- Nielsen Norman Group: https://www.nngroup.com/articles/gui-slider-controls/
