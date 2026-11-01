# OMORI Photo Album

Replika *PHOTO ALBUM* milik BASIL dari game **OMORI**, dibuat dengan satu file HTML.
Ada tiga versi album, semuanya dengan foto dan caption seperti di game:

| Album | Isi | Keterangan |
|---|---|---|
| **FARAWAY TOWN** | 48 foto (8 spread) | Album dunia nyata, caption bertanggal |
| **HEADSPACE** | 12 foto (2 spread) | Album di dunia mimpi |
| **BLACK SPACE** | 24 foto (4 spread) | Album "The Truth", caption sengaja dibuat buram seperti di game |

## Cara pakai

1. Buka halaman utama, lalu klik sampul atau judul buku yang mau dibuka.
2. Pakai tombol `<` dan `>` untuk membalik halaman.
3. Tombol panah kiri di pojok kiri atas untuk kembali ke pilihan buku.
4. Tombol speaker di sebelahnya untuk menyalakan atau mematikan musik.

Tidak perlu install atau build apa pun. Cukup buka `index.html` di browser.

## Struktur file

```
.
├── index.html          # seluruh halaman (HTML + CSS + JS)
├── images/
│   ├── background.jpg  # background halaman utama
│   ├── *AlbumCover.webp  # 3 sampul album
│   ├── FA_ALBUM_*.webp   # 48 foto Faraway Town
│   ├── DW_*.webp         # 12 foto Headspace
│   └── The_Truth_*.webp  # 24 foto Black Space
├── audio/
│   └── Event_maris_theme.ogg  # musik
└── README.md
```

## Sumber dan kredit

- **Foto dan sampul album:** [OMORI Wiki (Fandom) - PHOTO ALBUM](https://omori.fandom.com/wiki/PHOTO_ALBUM).
- **Caption:** teks asli dari game, dikutip lewat halaman wiki di atas.
- **Background:** fan art "[Omori background fan art :D](https://www.deviantart.com/carlyissleepy/art/Omori-background-fan-art-%3AD-922734588)" oleh **carlyissleepy** di DeviantArt.
- **Musik:** [*Event_maris_theme.ogg*](https://static.wikia.nocookie.net/omori/images/6/62/Event_maris_theme.ogg/revision/latest?cb=20210117051345) dari OMORI Wiki.
- **Font:** Lobster, Gloria Hallelujah, dan Redacted Script dari Google Fonts.
