#                                  <h1 align="center"> LudOS Bios 2022</h1>
<p align="center">
  Las Bios Correctas y necesarias para LudOS.
  The right and needed Bios for LudOS. 
</p>
<p align="center">
<img src="https://raw.githubusercontent.com/Luciano2018/RetroPieBios/master/logov3.png" alt="Raspberry Pi Buenos Aires" width="400" height="500"><img src="https://github.com/Luciano2018/LudOS-Bios/blob/main/LudOS.png" alt="Raspberry Pi Buenos Aires" width="400" height="500">
</p>

# Instalacion fácil-Easy Install:

Conectammos LudOS a Wifi o Ethernet, nos fijamos su IP, activamos SSH e iniciamos sesión desde otro dispositivo:
We need connect LudOS to Wifi or Ethernet, check the assigned IP, turn on SSH and login with other device:
- PC([Putty](https://www.putty.org/))
- Smartphone([ConnectBot](https://play.google.com/store/apps/details?id=org.connectbot&hl=es&gl=US))
- Iphone([Termius](https://apps.apple.com/pe/app/termius-ssh-client/id549039908))
- Raspberry Pi OS([Terminal](https://www.raspberrypi.com/documentation/computers/remote-access.html))

# Login:

User:`root`

Password: `ludos`

# Raspberry Pi:

Type:
```
wget -c https://raw.githubusercontent.com/Luciano2018/LudOS-Bios/main/LudOS_Bios.sh && sh LudOS_Bios.sh
```

# PC:

Type:
```
wget -c https://raw.githubusercontent.com/Luciano2018/LudOS-Bios/main/LudOS_Bios_PC.sh && sh LudOS_Bios_PC.sh
```
NOTE for PC Users, you can't just clone or download this repo like a zip file, because you will be missing 2 big bios needed for MelonDS, that are getting with the easy install Script from archive.org

# Tutorial: Retroconsolas
https://sites.google.com/view/raspberrypibuenosaires/retro-consolas

# Tutorial: Crea tu propio Joystick Arcade con Pro-Micro mejor que Zero Delay
https://sites.google.com/view/raspberrypibuenosaires/joystick-arcade
