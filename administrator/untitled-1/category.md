# Category

## Category

Category digunakan sebagai master untuk menentukan kategori masing-masing produk yang nantinya akan digunakan untuk mengkategorikan produk pada website hoky. 

 Untuk pengaturan kategori dilakukan oleh administrator pada menu _**Product Management**_, sub-menu _**Category**_

![Category Page](../../.gitbook/assets/image%20%28222%29.png)

### New Category

untuk melakukan penambahan kategori dilakukan dengan menekan tombol **New Category**

![Add New Category](../../.gitbook/assets/image%20%28162%29.png)

  
Berikut keterangan pada add new category:

| Kolom | Keterangan |
| :--- | :--- |
| Category Name | Nama dari kategori  |
| Slug | Digunakan untuk nama slug pada tautan |
| Brands | Diunakan untuk mengatur brands dari category |
| Parent | Pilihan parent untuk kategori yang akan ditambahkan, jika parent tidak diatur maka kategori akan dijadikan parent |

### Re-Order Category

Fitur Re-Order Category digunakan untuk mengubah urutan dari category yang sudah diatur sebelum. untuk mulai mengubah urutan kategori, tekan tombol **Re-Order Category**

![Re-Order Category](../../.gitbook/assets/image%20%28227%29.png)

Untuk mengubah urutan kategori, dapat dilakukan dengan sistem drag and drop kemudian simpan perubahan susunan kategori.

### Import Category

Pada menu Catergory terdapat fitur import menggunakan excel untuk memudahkan dalam proses penginputan data.

untuk memulai melakukan import brands dengan menekan tombol _**Import Category.**_

![Import Category Modal](../../.gitbook/assets/image%20%28252%29.png)

pertama **download form** untuk import data terlebih dahulu

![Download form import category](../../.gitbook/assets/image%20%2888%29.png)

Dalam Format import product terdapat 2 sheet; yang pertama category dan yang sheet kedua adalah Category set parent.

![Sheet Category](../../.gitbook/assets/image%20%28104%29.png)

Sheet Category digunakan untuk menginputkan seluruh category yang ada pada product.

![Sheet Category Perent Set](../../.gitbook/assets/image%20%2850%29.png)

Sheet Category Perant Set digunakan untuk mengatur sub kategrori dari category yang sudah dimasukan pada sheet category.

Berikut Keterangan untuk format import category:

| Kolom | Keterangan |
| :--- | :--- |
| Category Name \(Sheet category\) | Diisis dengan nama category \(boleh pakai simbol titik,koma, strip dll |
| Slug \(Sheet category\) | Di isi dengan kode unik untuk nama kategori, Slug hanya boleh di isi dengan huruf kecil, tanpa spasi, simbol yang diperbolehkan hanya \("-",a-z,1-0\) |
| Brand Key ID \(Sheet Category\) | Di isi dengan kode unik untuk nama brand \(slug\) harus sesuai dengan slug yang ada di brands |
| Category Slug\(Sheet category slug child set\) | Di isi dengan slug category child-nya |
| Parent Slug \(Sheet category parent set\) | Di isi dengan slug category parent-nya |
| Action \(Sheet category parent set\) | di isi dengan "add" atau "remove"; add ketika akan menambah/rubah data, renove ketika akan menghapus data |

### Export Category

Tekan tombol  _**Export category**_ untuk mengexport category, ada dua jenis cara export, yang pertama Export all \(export semua data yang ada di category\) dan selected export \(untuk export data yang sudah terchecklist\)

![Export Category](../../.gitbook/assets/image%20%2841%29.png)

Cek hasil download file excel category di folder download 

![file download category](../../.gitbook/assets/image%20%28157%29.png)



