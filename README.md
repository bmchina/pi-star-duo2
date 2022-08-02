This is a modified copy from offical Pi-Star 4.1.6 image.

Support NanoPI Duo2 and BH4DKU's MMDVM Duo2 hat.

Support ONLINE STM32 firmware flash.

You can download latest FULL image by join QQ group:691235280.


Custom installation ----

1）Download last Pi-Star image for NanoPI Air NEO and write to your TF card

http://www.pistar.uk/beta/Pi-Star_NanoPiAir_V4.1.4_08-Feb-2021.zip

2)Install patch for NanoPI Duo2

cd /tmp
sudo git clone https://github.com/bmchina/pi-star-duo2.git
cd pi-star-duo2
rpi-rw
sudo ./install.sh

