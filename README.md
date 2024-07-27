# Modul ESP32 Relay 1 Channel 
![](https://github.com/hwthinker/esp32-relay1ch/blob/main/picture/1.png)


## Cara download dengan jumper
![](https://github.com/hwthinker/esp32-relay1ch/blob/main/picture/3.png)
- Pasang serial USB TTL dengan ketentuan: 
   - TX -> RX USB Serial (Kabel Putih)
   - RX -> TX USB Serial (Kabel Hijau)
   - GND -> GND USB Serial (Kabel Hitam)
- Pastikan supply 9VDC dihubungkan pin VCC; GND Power supply -> GND
- pasang Jumper untuk menghubungkan IO0 terhubung GND
- Klik tombol reset (Tekan dan lepas tombol reset)
- Download program dan tunggu sampai selesai
- lepas jumper
- Klik tombol reset lagi untuk run-program
- ulang langkah awal bila melakukan download ulang lagi


## Cara download dengan Serial USB auto Download
![](https://github.com/hwthinker/esp32-relay1ch/blob/main/picture/2.png)
- Pasang serial USB TTL dengan ketentuan:
    - RX -> RX USB Serial  
    - TX -> TX USB Serial 
    - GND -> GND USB Serial  
    - IO0 -> IO# USB Serial 
    - EN -> EN# USB Serial
- Pastikan supply 9VDC dihubungkan pin VCC; GND Power supply -> GND
- Download program dan tunggu sampai selesai

⚠️ Note:
Anda dapat memilih untuk menggunakan power supply dari salah satu konektor berikut: konektor Micro USB atau konektor Power (berwarna hijau). Namun, Anda tidak bisa menggunakan kedua konektor secara bersamaan."