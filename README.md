Nama = Go Nadine Audelia

1. What is amqp?

AMQP atau Advanced Message Queuing Protocol adalah sebuah protokol standar terbuka pada lapisan aplikasi yang secara khusus dirancang untuk message-oriented middleware. Protokol ini memungkinkan berbagai sistem dan aplikasi yang berbeda untuk saling berkomunikasi dan bertukar pesan secara efisien dan aman. Dalam event ini, AMQP bertindak sebagai jembatan penghubung yang memastikan event dari publisher sampai ke message broker dan diteruskan ke subscriber. AMQP memiliki fitur-fitur penting untuk sistem seperti jaminan pengiriman pesan, queuing, routing, dan keandalan komunikasi. Selain itu, dengan menggunakan standar terbuka maka tidak perlu terikat pada satu vendor dan bisa dengan mudah berkomunikasi dengan layanan lain.

2. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?

String guest:guest@localhost:5672 adalah format URL standar yang digunakan oleh aplikasi untuk membangun koneksi ke message broker RabbitMQ. Guest pertama merujuk pada username yang telah dikonfigurasi di dalam instalasi RabbitMQ. Guest kedua melambangkan password yang digunakan untuk mengautentikasi pengguna. Bagian localhost:5672 menunjukkan alamat jaringan tempat message broker sedang beroperasi dan bersiap menerima koneksi masuk. Localhost berarti RabbitMQ dijalankan secara lokal di komputer sendiri, sedangkan 5672 adalah port jaringan default yang dialokasikan secara khusus untuk mendengarkan lalu lintas komunikasi protokol AMQP.

