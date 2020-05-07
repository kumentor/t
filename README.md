---
judul: "Menulis di Kumentor"
catatan: "Tulisan ini diterbitkan ke https://kumentor.now.sh/menulis/"
---

# Menulis di Kumentor

## Panduan Menulis
### Markah *Markdown*
Tulisan menggunakan bentuk berkas `.md` atau markah *Markdown*.
### Kepala (*Front Matter*) berisi Parameter
Kepala tulisan berbetuk `yaml` atau `toml`. Berikut ini contoh kepala tulisan:

```markdown
---
judul: "Judul Tulisan"
deskripsi: "Ini adalah deskripsi tulisan."
tanggal: "2019-12-30T23:59:59+07:00"
parameter: nilai
---

Isi **tulisan** dimulai di sini.
## Anak judul
```

Kepala tulisan berfungsi sebagai informasi dan *metadata* tulisan. Ditulis pada bagian awal tulisan. Kepala tulisan ditandai dengan `---` (tiga tanda minus) sebagai baris awal dan penutup. Sedangkan untuk bentuk `toml` kepala tulisan dibuka-tutup menggunakan `+++` (tiga tanda tambah).

Parameter di kepala tulisan bisa berisi selain `judul`, `deskripsi`, `tanggal`. Setiap nilai dari parameter dikutip menggunakan `"` (tanda petik).

Bentuk `yaml` bernilai jamak 
```yaml
parameter: 
- nilai1
- nilai2
- nilai3
```

Bentuk `toml` bernilai jalak 
```toml
parameter = [ "nilai1","nilai 2", "nilai3"]
```

#### Parameter `judul`

Parameter `judul` dan nilainya ditulis `judul: "Judul Tulisan"`.

#### Parameter `deskripsi`

Deskripsi bisa berisi abstrak tulisan. Parameter dan nilai `deskripsi` ditulis `deskripsi: "Ini adalah deskripsi tulisan."`.

#### Parameter `tanggal`

Tanggal bisa ditulis dalam bentuk:
+ `2019-12-30T23:59:59+07:00`
+ `2019-12-30T23:59:59`
+ `2019-12-30T23:59`
+ `2019-12-30`

#### Parameter lain