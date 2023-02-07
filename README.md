# VPS-SSH
OS
Debian 9 (HVM)
Debian 10
Berhasil di gunakan di vps aws dan os debian 9 hvm
untuk vps isp yg lain saya tidak tau, dan os yg lain juga saya tidak tau wkwk
Syarat && Bahan Untuk Menggunakan Script Ini
Wajib Punya VPS
Wajib Punya Akun Cloudflare
Wajib Punya Domain Punya Kamu Sendiri
Jika semua syarat dan Bahan sudah terpenuhi ,silahkan di coba script ini
Cara Install Script Nya
Login ke VPS kamu ( wajib pake user root)
MASUK KE VPS LALU KETIK
sudo su
Update Dulu VPS NYA
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
Otomatis Akan Reboot/ Hidupkan Ulang
Login Lagi Ke VPS NYA

Salin kode di bawah ini dan paste kan ke dalam vps punya kamu

maka proses install akan berjalan, jangan keluar dari vps
jika keluar dari vps saat lagi proses install,maka akan gagal
wget https://raw.githubusercontent.com/lizsvr/XRAY-MULTI/main/setup.sh && chmod +x setup.sh && ./setup.sh
jika sudah selesai,lalu ketik xmenu untuk menampilkan menu
menu
DONE / SELESAI
Info Perbaiki / FIX
NOTE
jika xray dan nginx mengalami error !
ketik
certxray
lalu ketik

restart-xray
INFO KODE SCRIPT
xmenu (untuk menampilkan menu original)
menu (untuk menampilkan menu mod)
updatedll (untuk update sc)
restart-xray (hidupkan ulang xray)
certv2ray/certxray (Perbarui Sertifikat / Update Certificate)
