# Virtual Machine dan Docker

Virtual machine merupakan teknologi yang penting untuk mendukung pengembangan dan operasional sebuah aplikasi. Selain virtual machine juga ada alternatif lain yaitu _container_. Virtual machine berjalan pada sebuah _hypervisor_, _container_ berjalan diatas _container engine_. Salah satu _container engine_ yang populer adalah Docker.

Penggunaan Docker lebih tepat digunakan pada kasus satu kontainer untuk satu tugas. Jadi misalkan sebuah website yang memiliki aplikasi web yang terhubung dengan database, maka akan memiliki satu kontainer untuk website dan satu kontainer lainnya untuk database.

Penggunaan kontainer dapat mendukung pengembangan aplikasi. _Image_ kontainer dapat dibuat semirip mungkin dengan infrastruktur yang digunakan untuk _operations_. Sehingga ketika proses development selesai, aplikasi yang dikembangkan dapat dengan mudah di-_deploy_ dan siap untuk beroperasi.
