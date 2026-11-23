1. Buat proyek Supabase dan jalankan database.sql di SQL Editor.
2. Isi DB_URL dan DB_ANON_KEY di index.html memakai Project URL dan anon key. Jangan gunakan service_role key pada browser. RLS hanya mengizinkan insert.
3. Chatbot ini menjawab FAQ umum secara lokal. Untuk jawaban AI generatif, hubungkan endpoint server-side yang terlindungi; simpan API key hanya sebagai secret server, jangan di HTML.
4. Atur masa retensi data kontak, batasi akses staf, dan tambahkan perlindungan spam sebelum publikasi.
