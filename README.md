# ScholarCraft Lite · @ramakertamukti Labs

Aplikasi authoring akademik ringan, statis, dan berbasis bukti untuk penelitian **kuantitatif maupun kualitatif**. Penulis cukup memasukkan **judul dan abstrak** untuk memperoleh draf awal *Introduction*, *Methodology*, *Results*, dan *Discussion* yang dapat diedit. Detail penelitian dan bukti dapat ditambahkan melalui panel *opsional*.

## Batasan ilmiah yang harus dipahami

- **Bukan model bahasa generatif atau sistem pencarian pustaka.** Teks disusun dengan aturan dan struktur akademik yang ditentukan dalam kode. Kualitas intelektual, ketepatan teori, dan kecukupan argumentasi tetap bergantung pada input dan revisi penulis.
- Aplikasi **tidak menemukan, memverifikasi, atau membuat** referensi, DOI, data lapangan, kutipan informan, statistik, prosedur penelitian, atau persetujuan etik.
- Bila bukti belum tersedia, naskah mempertahankan penanda `[PERLU DILENGKAPI: ...]` / `[REQUIRED: ...]`. Bagian Results tidak mengarang angka ataupun temuan.
- Tidak ada standar manuskrip tunggal bernama “Scopus Q1”; kesesuaian ditentukan oleh pedoman jurnal dan pertimbangan editor serta reviewer. Rekomendasi SRQR, COREQ, STROBE, CONSORT berlaku secara kondisional, terutama untuk bidang yang relevan.
- Metodologi **tidak dapat dinyatakan valid** hanya dari judul dan abstrak. Penulis harus mengisi rancangan, sampling, instrumen, analisis, mutu, dan etika yang benar-benar diterapkan.

## Cara memakai

1. Buka `index.html` atau publikasi GitHub Pages.
2. Isi judul, abstrak, pendekatan kuantitatif/kualitatif, dan bahasa.
3. Klik **Kembangkan draf ilmiah**. Periksa empat tab dan sunting teks.
4. Untuk naskah berbasis bukti, buka **Tambahkan bukti & detail metodologi** dan masukkan informasi asli. Klik kembali untuk regenerasi. *Regenerasi menimpa suntingan manual, dengan konfirmasi.*
5. Gunakan **Audit akademik** untuk meninjau bidang yang belum lengkap.
6. Unduh **Word `.docx` asli**, **TXT**, atau gunakan **Cetak / PDF** lalu pilih *Save as PDF* di dialog cetak browser.
7. Simpan proyek melalui **Backup JSON**, terutama saat pindah perangkat.

## GitHub Pages

1. Buat repository GitHub publik atau privat dengan Pages yang tersedia.
2. Unggah semua file dari folder ini **ke root repository**: `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, dan `icon-512.png`.
3. **Settings → Pages → Build and deployment → Deploy from a branch**; atur `main` dan `/(root)`.
4. Buka `https://USERNAME.github.io/REPO/` setelah Pages selesai terbit.
5. Pada perangkat/browser yang mendukung, gunakan **Install app** atau **Add to Home Screen**. PWA membutuhkan HTTPS; akses via `file://` tidak dapat memasang service worker.

## Data & keamanan

Penyimpanan proyek memakai `localStorage` dari browser. Data **tidak dikirimkan ke server** oleh aplikasi ini. Pada GitHub Pages, sumber kode terpublikasi, bukan isi proyek yang tersimpan lokal. Jangan masukkan informasi partisipan yang mengidentifikasi orang bila tidak diperlukan; unduhan JSON menyalin semua input yang diisikan.

## Dasar struktur

- Dokumen pengguna: *How to Write and Publish: Steps for Journal Indexing, SCOPUS Selection, and Peer-Reviewed Submissions*, terutama halaman 3–7 (komponen artikel) dan halaman 14–16 (persiapan submission).
- ICMJE, [Preparing a Manuscript for Submission](https://www.icmje.org/recommendations/browse/manuscript-preparation/preparing-for-submission.html): struktur IMRaD, metode yang cukup rinci, peran hasil dan pembahasan.
- EQUATOR Network: [reporting guidelines](https://www.equator-network.org/), misalnya SRQR/COREQ dan STROBE/CONSORT untuk konteks studi yang sesuai.

Copyright label: **@ramakertamukti Labs**. Tidak ada klaim afiliasi atau sertifikasi resmi dengan Scopus/Elsevier.
