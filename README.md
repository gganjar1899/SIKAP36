# SIKAP 36
Sistem Informasi Kebiasaan Anak Pelajar - SMPN 36.

Aplikasi web statis: `index.html` + `logo-7kaih.png`. Data disimpan di Supabase.

## Pasang di Vercel
1. Unggah isi folder ini (bukan berkas .zip) ke repositori GitHub Private.
2. Di Vercel: Add New > Project > pilih repositori > Deploy. Tidak perlu pengaturan build.

## Catatan keamanan
- Yang tertanam di index.html hanya alamat proyek dan kunci publik (anon) Supabase.
- Jangan pernah menaruh kunci `service_role` di repositori ini.
- Akses data diatur oleh aturan RLS di database.
