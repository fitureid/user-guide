---
description: >-
  Product management adalah pengaturan barang/produk yang akan diperjualbelikan
  dan kategori yang ada pada produk
---

# Product Management

## Product

Produk merupakan barang yang akan diperjualbelikan. Untuk melakukan pengaturan pada product dilakukan dengan mengakses menu **Product Management**, sub-menu **Product.**

![Product Page](../../.gitbook/assets/image%20%28177%29.png)

### New Product

Untuk melakukan penambahan produk, dilakukan dengan menekan tombol **New Product**

![Add new product](../../.gitbook/assets/image%20%28152%29.png)

Berikut keterangan untuk proses add new product \(Product Information\):

| Kolom | Keterangan |
| :--- | :--- |
| Product Image | Pengaturan gambar untuk image, direkomendasikan memilki 3-5 gambar terbaik dan menarik untuk pembeli \(format  JPG .JPEG .PNG max 10 MB\) |
| Product Name | Nama dari produk |
| Brand | Pengaturan brand dari produk |
| Category | Pengaturan Kategori dari produk |

Berikut keterangan untuk proses add new product \( Price\):

<table>
  <thead>
    <tr>
      <th style="text-align:left">Kolom</th>
      <th style="text-align:left">Keterangan</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Price</td>
      <td style="text-align:left">Harga produk dalam bentuk rupiah</td>
    </tr>
    <tr>
      <td style="text-align:left">Product Stock</td>
      <td style="text-align:left">Inputan untuk jumlah stok pada produk, Stok akan berkurang otomatis ketika
        ada proses penjualan barang</td>
    </tr>
    <tr>
      <td style="text-align:left">Product Variant</td>
      <td style="text-align:left">
        <p>Digunakan untuk melakukan pengaturan varian dari produk</p>
        <p>Pengaturan dilakukan untuk gambar, Nama varian, harga, kode SKU (unique
          code) dan stok masing-masing varian</p>
      </td>
    </tr>
  </tbody>
</table>Berikut keterangan untuk proses add new product \(Management\):

| Kolom | Keterangan |
| :--- | :--- |
|  SKU  \(Stock Keeping Unit\)  | kode unik yang diberikan kepada setiap item barang baik yang dibeli maupun dijual |
|  Product description | Deskripsi lengkap mengenai produk |

Berikut keterangan untuk proses add new product \(Delivery\):

| Kolom | Keterangan |
| :--- | :--- |
|  Weight  | Berat dari produk \(kilogram atau gram\) |

### Import

Pada menu Product terdapat fitur import menggunakan excel untuk memudahkan dalam proses penginputan data.

untuk memulai melakukan import brands dengan menekan tombol _**Import Product.**_

![Import product page](../../.gitbook/assets/image%20%2819%29.png)

pertama **download form** untuk import data terlebih dahulu

![Download format excel ](../../.gitbook/assets/image%20%2831%29.png)

![Format Excel Import](../../.gitbook/assets/image%20%28103%29.png)

Pada format excel ada 2 sheet yang tersedia, yang pertama adalah Product. Berikut keterangan lengkapnya:

| Kolom | Keterangan |
| :--- | :--- |
| Product Name | Nama dari produk |
| SKU | kode unik yang diberikan kepada setiap item barang baik yang dibeli maupun dijual |
| Brand | Pengaturan dari brand untuk produk \(disesuaikan dengan brand yang sudah dimasukan ke dalam sistem\) |
| Category | Pengaturan dari kategori untuk produk \(disesuaikan dengan category yang sudah dimasukan ke dalam sistem\) |
| Price \[min\] | Harga minimum produk |
| Price \[max\] | Harga maximum produk |
| Product Stock | Inputan untuk jumlah stok pada produk, Stok akan berkurang otomatis ketika ada proses penjualan barang |
| Product Description | Deskripsi lengkap untuk produk |
| Weight \[unit\] | Disikan dengan jenis berat dari produk \(g/kg\) |
| Weight \[Value\] | Disikan dengan berat dari produk |
| Main Image \[url\] | Hal yang perlu diperhatikan dalam pengisian form import untuk image adalah image url. url image diambil dari proses **Upload Image** |

Yang kedua adalah sheet Variant. Berikut keterangan lengkapnya:

| Kolom | Keterangan |
| :--- | :--- |
| Product SKU | kode unik ini disesuaikan dengan kode SKU produk pada sheet Product |
| Variant Key Name | Nama variant dari produk |
| Image Variant Url | Hal yang perlu diperhatikan dalam pengisian form import untuk image adalah image url. url image diambil dari proses **Upload Image** |
| Price | Harga dari variant |
| SKU | Isikan dengan kode unik untuk variant  |
| Stock | jumlah stok untuk masing-masing variant |

### Export

Proses export Product digunakan untuk melakukan pengambilan data product yang ada disistem yang di konvert dalam bentuk excel. 

![export product](../../.gitbook/assets/image%20%2853%29.png)

Ada dua jenis proses export pada product :

#### All Export Product

Untuk melakukan export all product dengan menekan tombol **Export Product** pilih **ALL,** otomatis semua data brands akan terdownload.

#### Export Selected

Untuk melakukan export selected product, pertama pilih file yang ingin di export, kemudian tekan tombol **Export Product**, Pilih **Selected**, otomatis data yang terpiih akan terdownload.

