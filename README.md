# Nethunter-In-Termux
Ini adalah script untuk anda lakukan proses kemasukan ke dalam Sistem Terminal untuk Termux install Kali nethunter (Kali Linux) jadi anda yang pin ada untuk purchased ini.Link kan dengan github ini.
### Steps For Installation
1. MuatTurun script di buka Termux taip "cd" dan enter,Paparan terus copy step ini di terminal **HOME** `curl -LO https://raw.githubusercontent.com/kasuhabot/Nethunter-In-Termux/master/kalinethunter`
2. Bagi kebenaran keizinan `chmod +x kalinethunter` tekan enter
3. Mulakan script untuk aktif nethunter taip` ./kalinethunter` enter

### Usage 
1. Gunakan kata arah `startkali` untuk menggunakan nethunter. Secara sendiri User guna Default __kali__ dan default password sama  __kali__. akan nama papar kali@kali atau kali@localhost .
2. Anda nak gunakan nethunter dengan User secara root gunakan kata arah `startkali -r`.

### VNC Guide
1. To start a vnc session `vnc start`
2. To stop a vnc session `vnc stop`
3. To check status ( Display and port number) of vnc session `vnc status`
4. If user is __kali__ then by default `vnc start` will start vncserver with `DISPLAY=:2` & `PORT=5902` and for root user `DISPLAY=:1` & `PORT=5901`


### In Case Of SSL error: certificate verify failed
Rerun script with extra parameter `--insecure` or copy paste this command `./kalinethunter --insecure`

#### setup LXDE 
Default __DESKTOP__ is _XFCE4_ but you can setup __LXDE__ also https://www.hax4us.com/2018/07/how-to-install-lxde-in-kali-nethunter.html?m=1

#### You have any idea to improve ? So Just give PR
