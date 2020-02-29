# LinuxDebian
tente su
1º download Linux non free firmware
  1-1 https://cdimage.debian.org/mirror/cdimage/unofficial/non-free/cd-including-firmware/current/amd64/iso-dvd/
2º Using BootPenDrive Universal Usb Installer
  1-instalação
  https://www.youtube.com/watch?v=K6fmTgq8DRs&t=1213s
3º Instalar drivers
  1-https://www.youtube.com/watch?v=Tc7LZ1RLGUs
  3-1-sudo apt install firmware-ipw2x00 wireless-tools
  3-2-sudo apt-get update && apt-get install firmware-iwlwifi
  3-3-modprobe -r iwlwifi ; modprobe iwlwifi (pode não funcionar)
4º Instalar chrome
  4-1º - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
  4-2 - sudo apt install ./google-chrome-stable_current_amd64.deb
