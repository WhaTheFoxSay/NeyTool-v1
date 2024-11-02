# NeyTool-v1
Tool Network for Diagnose Latency and Lookup IP and domain

NeyTool
Sebuah Software sederhana sebagai tool diagnosis pada network.
Umumnya tool ini sudah ada pada bawaan desktop/server Linux yang kita install. Namun, disini saya membuatnya ringkas dalam satu kode dimana kita bisa memilih antara 3 diagnosis yang ada.
- Ping
- Traceroute
- Lookup

NeyTool ditulis menggunakan C++ dimana memakai boost/Asio sebagai library utama (librari yang lebih mendukung untuk develop program yang berhubungan network).

Sekian dan terima kasih


Depedency :
- boost-devel
  
(Cara Install Depedency)
Debian/Ubuntu: sudo apt install libboost-all-dev
Fedora: sudo dnf install boost-devel
Arch Linux: sudo pacman -S boost

Cara install Tool : 
- Download file dan masuk ke dir dari file tersebut via terminal
- Compile dengan cara berikut
  `g++ -o ruth ruth.cpp -lboost_system`
- Lalu running dengan cara berikut
  `./ruth //Alamat Ip atau Alamat Domain' (contoh ./ruth fer.dinan.one)
- Setelah itu anda akan masuk ke aplikasi
  
