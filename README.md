# Wordlist Indonesia

100.000 entri password umum pola Indonesia untuk pengujian keamanan WiFi sendiri.

- Kata Indonesia umum, nama orang, nama kota/kabupaten
- Pola angka populer (12121212, 17081945, dll)
- Slang, bahasa alay/leet speak
- Kredensial default (admin, password, dll)
- Kombinasi 2 kata

## Pakai

```bash
wget https://raw.githubusercontent.com/misbahkun/wordlist-indonesia/main/wordlist-indonesia.txt
aircrack-ng -w wordlist-indonesia.txt handshake.cap
```

> Hanya untuk menguji jaringan milik sendiri / yang kamu punya izin.
