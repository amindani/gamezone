# GameZone

Katalog game dan editorial dengan HTML, CSS, JavaScript, dan Supabase.

## Deploy GitHub Pages
Settings → Pages → Deploy from a branch → main → /(root).

## Supabase
Frontend menggunakan publishable key dan tabel dengan RLS read-only. Jangan pernah memasukkan service-role key ke browser. Skema database tersedia di supabase/schema.sql.

## Artwork
Situs akan menampilkan artwork placeholder jika gambar lokal belum tersedia. Letakkan cover di assets/games/ dengan nama yang sama seperti kolom cover_path pada tabel games.