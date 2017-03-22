# Catatan pengembangan:

## 21/03/2017
### HTML
#### Desain ulang template
##### Home page
1. Menambah total kolom di home page menjadi 3 kolom (2 sidebar, 1 home post)
> Kolom pertama **Sidebar1**, kolom kedua **Home post**, kolom ketiga **Sidebar2**. Pengeturan kolom masih menggunakan **Grid system**, fitur andalan _Bootstrap_. lg-4 md-4 sm-6 xs-12.
>> Sidebar1 memakai 4 grid, jika mode col-md atau col-lg maka letaknya di kolom pertama. Jika lebih kecil (col-sm dan col-xs), maka letaknya di bawah **Home post**.

>> Home post memakai 5 grid, posisi berubah sesuai penjelasan di atas. lg-5 md-5 sm-12 xs-12.

>> Sidebar2 memakai 3 grid, letaknya paling kanan/bawah. Posisi jika mode sm, maka akan berdampingan dengan **Sidebar1** berada di bawah **Home post**. lg-3 md-3 sm-6 xs-12.
2. Home post, menggunakan element **List Group** bawaan Bootstrap.
3. Sidebar widget menggunakan element **Panel** bawaan Bootstrap.
4. Paging di ubah ke Pager, style menggunakan **Pager** bawwan Bootstrap.
