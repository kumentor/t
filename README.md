---
judul: "Menulis di Kumentor"
---

# Menulis di Kumentor

## Panduan Menulis
### Markah *Markdown*
Tulisan berbentuk `.md` atau markah *Markdown*.
### Kepala (*Frontmatter*) berisi Parameter
Kepala tulisan berbetuk `.yml` atau `.toml`. Berikut ini contoh kepala tulisan:

```md
---
judul: "Judul Tulisan"
deskripsi: "Ini adalah deskripsi tulisan."
tanggal: "2019-12-30T23:59:59+07:00"
parameter = nilai
---

Isi **tulisan** dimulai di sini.
## Judul lain
```

Kepala tulisan berfungsi sebagai informasi dan metadata tulisan. Ditulis pada bagian awal tulisan. Kepala tulisan ditandai dengan `+++` (tiga tanda tambah) sebagai baris awal dan penutup. Parameter kepala tulisan bisa berisi selain `judul`, `deskripsi`, `tanggal`. Setiap nilai dari parameter dikutip menggunakan `"` (tanda petik).

Untuk parameter bernilai jamak, diselubungi kurung kotak dan dipisahkan tanda koma.

Bentuk `.yaml`
```
parameter: 
- nilai1
- nilai2
- nilai3
```

Bentuk `.toml`
```
parameter = [ "nilai1","nilai 2", "nilai3"]
```

#### Parameter `judul`

Nilai dari parameter `judul` ditulis seperti berikut: `judul: "Judul Tulisan"`.

#### Parameter `deskripsi`

Deskripsi bisa berisi abstrak tulisan. Nilai dari parameter `deskripsi` ditulis seperti berikut: `deskripsi: "Ini adalah deskripsi tulisan."`.

#### Parameter `tanggal`

Tanggal bisa ditulis dalam bentuk:
+ `2019-12-30T23:59:59+07:00`
+ `2019-12-30T23:59:59`
+ `2019-12-30T23:59`
+ `2019-12-30`

#### Parameter lain untuk kepala tulisan
##### Kategori Buku
##### Kategori Dokumen
##### Kategori Tutor