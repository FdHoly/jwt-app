Joey Vilbert 185150707111001
Step :
 1. Membuat project lumen baru dengan command "composer create-project --prefer-dist laravel/lumen jwt-app"

 2. Menjalankan command "composer require tymon/jwt-auth" di command prompt windows.

 3. Menkonfigurasi file app.php pada bootstrap untuk mengaktifkan beberapa fitur seperti eloquent, fascades, middleware auth, dan mendaftarkan JWT.

 4. Melakukan update composer dengan composer update lalu mengenerate secret key untuk jtw "php artisan jwt:secret"

 5. Membuat migration user dan menyesuaikan dengan skema pada modul lalu mengeksekusi migration

 6. Mengubah file model user dan menyesuaikan dengan kebutuhan database

 7. Membuat folder baru yaitu config berisikan file auth.php untuk autentikasi token api

 8. Memodifikasi route pada web.php dan UserController.php sesuai dengan fungsi yang ada yaitu untuk register, login, logout 

 9. Melakukan percobaan project dengan pertama melakukan registrasi 2 pengguna dengan route /auth/register dengan method post

 10. Melakukan login pada user yang sudah diregistrasi dengan method post

 11. Melihat list pengguna dengan menggunakan token yang didapat pada saat login di bagian authorization dengan method get

 12. Melihat pengguna yang sedang digunakan untuk login dengan token dengan method get

 13. Melakukan logout dengan method get

 14. Membuat repository github dengan nama jwt-app dan melakukan push dengan commit "JSON Web Token Lengkap"