# Add-Port-Use-UFW-Uncomplicated-Firewall-
Add port use ufw 

Izinkan Port TCP:

    sudo ufw allow [nomor_port]/tcp

Izinkan Port UDP:

    sudo ufw allow [nomor_port]/udp

Melihat Daftar Aturan Firewall

    sudo ufw status

Melihat Port yang Sedang Digunakan

    sudo netstat -tuln

Menggunakan netstat
Perintah netstat digunakan untuk menampilkan semua koneksi jaringan dan port yang sedang digunakan:

    sudo netstat -tuln

Menggunakan ss
ss adalah alat modern untuk menampilkan informasi tentang soket:

    sudo ss -tuln

Menggunakan lsof
lsof (List Open Files) juga bisa digunakan untuk melihat port yang sedang digunakan:

    sudo lsof -i -P -n
