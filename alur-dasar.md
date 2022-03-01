# Alur Dasar Git

## 1 - Inisiasi Git
```
git init
```
## 2 - Alur Push Perubahan ke Git Remote
### 2.1 Pilih Branch
- Untuk membuat branch baru dan pindah ke branch tersebut
```
git checkout -b <branch>
```
- Bila nama branch ternyata sudah ada, tinggal hilangkan -b
```
git checkout <branch>
```

### 2.1 Git Add
Fungsi: menambahkan file untuk dicommit

- Kalau hanya ingin menambahkan 1 atau bererapa file saja untuk di commit, 
```
git add file.txt file2.txt
```
- Kalau ingin menambahkan semua file untuk di commit
```
git add .
```

### 2.2 Git Commit
Fungsi: mengcommit/menyimpan perubahan secara lokal(pc masing2)

bagian `<komentar>` diisi dengan pesan sesuai perubahan, misalnya: "edit isi file.txt"
```
git commit -m "<komentar>"
```

### 2.3 Git Push  
Fungsi: push perubahan ke remote(github)

`<branch>` diisi sesuai nama branch yang diinginkan
```
git push origin <branch>
```

