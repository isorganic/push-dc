# push-dc
script in digunakan untuk push role dc menggunakan chat. Terdapat auto delete massage agar aman tidak terdeteksi bot. Script ini butuh python3 (atai terbaru)  sama colorama. 

##Instalasi
1. Install Screen
    ```bash
   apt install screen
2. Lalu buat screen
   ```bash
   screen -S dc
3. Selanjutnya git clone repositori dan masuk ke cd
   ```bash
    git clone https://github.com/isorganic/push-dc && cd push-dc
4. edit ```token.txt``` sesuai autorization discord masing-masing
   ```bash
   nano token.txt
6. Jalankan program m
   ```bash
   python3 main.py
  
Keterangan:
1. Butuh autorize discord dapat kalian cari di mode developer pake chrome (laptop/pc), kimis & mises (HP)
2. ID channel kalian copy room chat discord, lalu ambil angkanya. itu id discord/channel
3. Set time untuk hapus pesan
4. set time untuk mengirim pesan
5. kalo mau edit pesan, tinggal edit di ```pesan.txt```
