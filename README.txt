SOLAR MONITORING - PAKET LAYOUT REFERENSI

Paket ini mempertahankan dashboard 3 kolom (sidebar kiri, monitoring utama, riwayat kanan) sesuai gambar referensi.

CARA PASANG CLOUDFLARE PAGES:
1. Ekstrak ZIP ini.
2. Upload isi folder ini secara langsung (index.html harus di root), bukan folder pembungkus.
3. Deploy ulang.
4. Jika masih tersimpan versi lama, buka site settings/browser site data dan hapus cache/service worker lama, lalu refresh.

Field ThingSpeak yang diasumsikan:
Field 1 = tegangan PZEM, Field 2 = arus PZEM, Field 3 = daya PZEM, Field 4 = energi kumulatif, Field 5 = tegangan JK BMS, Field 6 = arus JK BMS, Field 7 = SOC, Field 8 = suhu baterai.
Daya keluar baterai dihitung sebagai tegangan BMS x arus BMS jika arus positif berarti discharge. Jika BMS Anda menggunakan tanda terbalik, logika tanda arus perlu dibalik.
