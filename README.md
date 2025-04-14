# 💬 Implementasi Pemilihan Quote Menggunakan Assembly x86

## Deskripsi  
Program ini dibuat menggunakan bahasa **Assembly NASM (x86 32-bit)** dan berfungsi untuk menampilkan **kutipan motivasi (quote)** berdasarkan input angka dari pengguna (1–5). Jika input berada di luar rentang tersebut, maka program akan menampilkan **pesan error**.

---

## Fitur  

- **Input angka** dari pengguna (1–5)  
- **Menampilkan quote** sesuai pilihan  
- **Validasi input** agar tetap dalam rentang  
- **Konversi karakter** ke angka  
- **Sistem I/O** menggunakan syscall Linux (`int 0x80`)  
- Penyimpanan data quote menggunakan **array pointer**  

---

## Konsep yang Digunakan  

- **`int 0x80` syscall Linux** (read/write/exit)  
- **Register handling** dan **memory management**  
- **Looping dan branching** (`cmp`, `jmp`, `jl`, `jg`)  
- Segment `.data`, `.bss`, dan `.text`  
- **Konversi ASCII ke Integer** (manual parsing)  

---

## Tools  

- **Assembler**: **NASM**  
- **Platform Uji Coba**:  
  [TutorialsPoint Online x86 Assembly Compiler](https://www.tutorialspoint.com/compilers/online-assembly-compiler.htm)  
- **Arsitektur**: x86 (32-bit)  

---

## I/O Gambar

Berikut adalah contoh tampilan **I/O** yang menunjukkan proses input angka dari pengguna dan keluaran quote yang sesuai:

![Contoh I/O Gambar](!![image](https://github.com/user-attachments/assets/01efc174-92ef-4b17-b9cb-e1d6312a4b01)()


---
## Tujuan Pembelajaran  

- **Memahami pemrograman low-level** dengan Assembly  
- **Mempelajari penggunaan syscall** dan I/O di Linux  
- Membuat aplikasi **interaktif sederhana** menggunakan NASM  
