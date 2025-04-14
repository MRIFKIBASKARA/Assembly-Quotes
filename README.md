📌 Implementasi Pemilihan Quote Menggunakan Bahasa Assembly pada Arsitektur x86
📖 Deskripsi
Program ini ditulis dalam bahasa Assembly NASM dan berjalan pada arsitektur x86 (32-bit). Fungsinya sederhana: menerima input angka dari pengguna (1–5), kemudian menampilkan quote motivasi berdasarkan input tersebut. Jika input tidak valid (bukan angka 1–5), program akan memberikan pesan kesalahan.

Program ini dapat dijalankan secara lokal dengan NASM dan juga diuji secara online melalui platform seperti TutorialsPoint Online Assembly Compiler.

🧩 Fitur Program
Menerima input angka dari pengguna (1–5)

Menampilkan quote motivasional sesuai input

Validasi input dengan pesan error jika di luar rentang

Konversi input ASCII ke integer

Penggunaan array pointer untuk menyimpan daftar quote

I/O menggunakan system call Linux (int 0x80)

🧠 Konsep yang Digunakan
Sistem Call Linux (int 0x80) untuk keperluan I/O

Register manipulation dan pemrosesan data tingkat rendah

Array pointer untuk akses dinamis ke data

Branching logic menggunakan cmp, jl, jg, jmp

Segmentasi memori: .data, .bss, .text

🛠 Tools
Assembler: NASM (Netwide Assembler)

Platform uji coba: TutorialsPoint x86 Online Compiler

Target Arsitektur: x86 / 32-bit Linux

🎯 Tujuan Pembelajaran
Mempelajari dasar pemrograman Assembly NASM pada Linux

Mengenal sistem call dan mekanisme I/O level rendah

Mengembangkan program interaktif sederhana berbasis teks
