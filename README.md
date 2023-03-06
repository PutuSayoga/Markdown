# MARKDOWN
  
- Markdown merupakan sebuah bahasa markup yang ringan yang bisa ditambahkan untuk memformat sebuah element pada dokumen plaintext.
- Dibuat oleh John Gruber pada tahun 2004
- Menggunakan markdown berbeda dengan menggunakan WYSIWG (seperti pada Ms. Word). Pada Ms. Word, kita mengklik sebuah tombol untuk memformat suatu text, dan perbahannya dapat dilihat saat itu juga. Sedangkan markdown tidak seperti itu, kita menambahkan syntax markdown pada sebuah text untuk mengidentifikasi kata mana dan phrase mana yang berbeda.
- Kita bisa menambahkan markdown sendiri, tersedia juga aplikasi yang membantu kita menambahkan markdown. Tergantung dari aplikasi yang digunakan, kita mungkin tidak dapat melihat perubahannya secara langsung. Namun, hal itu lumrah. berdasarkan Gruber, syntax markdown didesain agar dapat dibaca walaupun perubahan belum dapat dilihat

  > The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.

## Mengapa Menggunakan Markdwon?

- Bisa digunakan untuk menulis apa saja, contoh: website, documents, note, books, presentations, email, dan dokumentasi teknikal
- Bisa dipindahkan. Berbeda dengan Ms. Word, markdown dapat dibuka dari aplikasi apa saja selama aplikasi tersebut mendukung markdown
- Tidak bergantung pada platform, jadi bisa digunakan pada OS manapun
- "Future proof". Walaupun aplikasi yang digunakan berhenti bekerja, kita tetap dapat membaca dokumen markdown tersebut menggunakan text editor
- Markdown ada dimana-mana, website seperti Reddit dan Github mendukung markdown, dan banyak aplikasi desktop dan web-based mendukung ini

## Bagaimana Cara Kerja nya?

- Markdown berekstensi .md atau .markdown
- Aplikasi meng-convert text yang berformat markdown ke HTML supaya ditampilkan pada web browsers
- Aplikasi markdown menggunakan sesuatu yg disebut "Markdown processor" (atau parser atau implementation) untuk melakukan proses penampilan menjadi HTML.

Singkatnya:

1. Buat file berekstensi .md / .markdown
2. Buka file tersebut pada aplikasi markdown
3. Gunakan aplikasi tersebut untuk meng-convert file markdown ke dokumen HTML
4. Lihat dokumen HTML tersebut pada web browser atau dalam format lain (seperti pdf)

## Markdown bisa dipakai apa?

### Website

Markdown didesain untuk web, jadi tidak heran banyak konten ditampilkan menggunakan markdown. Cara sederhana membuat website dengan markdown (blot.im & smallvictori.es). Static web generator (Jekyll, salah satu yang bisa posting gratis pada GitHub). Content Management System (Ghost)

### Documents

Cukup bagus untuk membuat dokumen sederhana seperti tugas dan surat.

### Notes

Markdown merupakan solusi ideal untuk membuat catatan. Kita bisa menggunakan aplikasi catatan yang mendukung mardown seperti: Simplenote, Notable, Bear, Boostnote

### Books

Coba Leanpub, layanan yang bisa membuat file markdown kita menjadi e-book

### Presentations

Percaya atau tidak, kita bisa menggunakan markdown untuk membuat presentasi. Membuat presentasi menggunakan markdown membutuhkan keahlian lebih, namun jika sudah terbiasa akan lebih mudah daripada menggunakan aplikasi seperti PowerPoint atau Keynote. Remark, Cleaver, Marp merupakan markdown slideshow berbasis web (Deckset, Hyperdeck, Marked untuk Mac)

### Email

Jika kita kesulitan melakukan format pada pesan email setiap kali kita ingin mengirim emal, markdown bisa menjadi solusinya. Markdown Here dapat meng-convert file markdown menjadi HTML yang siap kirim

### Collaboration

kolaborasi dan team merupakan cara yang populer untuk berkomunikasi dengan teman kerja. Aplikasi ini tidak mendukung semua fitur markdown, namun beberapa fitur seperti bold dan italic sangat berguna tanpa perlu menggunakan antar muka WYSWIG. (Slack, Discord, Mattermost)

### Documentation

Markdown merupakan solusi alami untuk membuat dokumentasi teknis. Layanan seperti GitHub sedang gencar-gencarnya berpindah menggunakan markdown untuk dokumentasinya. beberapa alat bantu yang bisa dipakai: Read the Doc, MkDocs, Docusaurus, VuePress, Jekyll

## "Flavors" dari Markdown

- Salah satu hal yang membingungkan dari markdown adalah setiap aplikasi markdown (tidak semua, tapi kamu mengertilah apa maksudnya) menggunakan versi markdown yang sedikit berbeda. Variasi dari versi ini biasanya disebut "Flavors". Tugas kita untuk terbiasa menggunakan flavor apa yang digunakan pada aplikasi / layanan yang kita pakai
- Hal ini berarti kita tidak akan pernah tahu secara jelas jika suatu aplikasi / layanan menyatakan meraka mendukung "markdown". Apakah mereka menggunakan syntax dasar saja? atau kombinasi dari sintax yang diextent?. Kita tidak akan pernah tahu sampai kita membaca dokumentasi mereka atau mulai menggunakan aplikasi tersebut
- Saran terbaik ketika kita baru memulai adalah memilih aplikasi yang memiliki dukungan markdown yang baik (dokumentasi, dll) agar lebih mudah kedepannya

## Sumber Tambahan

- <https://daringfireball.net/projects/markdown/> dokumentasi markdown John Gruber, panduan original yang ditulis penciptanya
- <https://www.markdowntutorial.com/> website yang dapat dipakai untuk mencoba markdown
- <https://github.com/mundimark/awesome-markdown> list alat bantu markdown yang bisa dipakasi sebagai sumber
