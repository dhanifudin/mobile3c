# Pertemuan 02

## Rangkuman Android Basic XML Layouts

1. Pada pertemuan 2 ini belajar desain UI dari kombinasi kotak bersarang yang lebih sederhana yang menunjukkan bagian dalamnya menggunakan orientasi horizontal atau vertikal.

2. Container Android yang umum digunakan adalah LinearLayout (the box model), RelativeLayout (a rule-based model), TableLayout (the grid model),ScrollView, dll.

3. Untuk menggunakan Relative Notation di Properties, yang harus kita lakukan adalah :
- Letakkan identifikasi (android:id attributes) pada semua elemen yang akan kita gunakan.
- Sintaksnya adalah: @+id/... (misalnya kotak EditText bisa disebut XML: Android:id="@+id/ediUserName")
- Referensikan widget lain menggunakan nilai identifikasi yang sama (@+id/...) yang sudah diberikan ke widget. Misalnya kontrol di bawah kotak EditText : Android:layout_below="@+id/ediUserName"

4. Berdasarkan live coding penjelasan bapak dosen, yang saya pahami adalah tentang pembuatan button yang mana button ini harus bergantung pada salah satu/beberapa line sisi (atas/bawah/kanan/kiri). Untuk pembuatan beberapa button pada 1 layout bisa menggunakan garis bantu untuk memudahkan pengaturannya. Setelah belajar tentang layout, dilanjutkan penjelasan tentang activity agar button tadi bisa dioperasikan (misalkan ketika button diklik maka akan diarahkan pada halaman layout lain). Pembuatan activity bisa dilakukan pada file MainActivity.java ataupun juga bisa melalui AndroidManifest.xml tergantung pada kita sendiri nyamannya pakai yang mana.








