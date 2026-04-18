---
title: "Belajar Bahasa Pemrograman Zig"
type: "docs"
weight: 1
bookToC: true
---

# Selamat Datang di Panduan Zig

Bahasa pemrograman **Zig** adalah bahasa pemrograman sistem yang bersifat *general-purpose* (serba guna). Zig dirancang untuk bersaing dengan C dan menggantikannya, dengan fokus utama pada keamanan, keterbacaan, dan efisiensi tanpa adanya *hidden control flow* (alur kontrol yang tersembunyi).

### Mengapa Belajar Zig?

* **Sederhana:** Tidak ada *macro* yang rumit, tidak ada *preprocessor*, dan tidak ada *operator overloading*. Apa yang Anda lihat adalah apa yang dieksekusi.
* **Manajemen Memori yang Jelas:** Zig tidak memiliki *garbage collector* bawaan, melainkan memberikan kontrol alokasi memori secara penuh kepada pemrogram melalui *Allocator*, menjadikannya sangat aman dan dapat diprediksi.
* **Comptime:** Kemampuan metaprogramming yang sangat kuat; Anda dapat mengeksekusi kode biasa pada saat waktu kompilasi (*compile-time*).
* **Interoperabilitas dengan C:** Zig dapat mengimpor *header* C secara langsung dan mengompilasi kode C/C++ secara bawaan (native).