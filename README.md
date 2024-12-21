# R-Pi3---Kedei-LCD

## FRANÇAIS

Pour l'installation de votre **écran Kedei** en version **6.1**, **6.2** ou **6.3**, vous aurez besoin d'installer une version **Raspberry Pi OS (Legacy, 32-bit) (Debian Bullseye)** via **Raspberry Pi Imager**.

Ensuite, il vous faudra télécharger ce fichier :  
[https://drive.google.com/file/d/14IInCRz6D3J-bQauS-rAxSeOSncNUjd4/view](https://drive.google.com/file/d/14IInCRz6D3J-bQauS-rAxSeOSncNUjd4/view)

Transférez ce fichier sur votre Raspberry Pi et exécutez les commandes suivantes :

```bash
tar -xzfv LCD_show_v6_1_3.tar.gz
cd LCD_show_v6_1_3
sudo ./LCD35_v     # Pour basculer sur l'affichage écran de votre Pi
sudo ./LCD_hdmi    # Pour basculer sur l'affichage HDMI de votre Pi
