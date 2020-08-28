# VanillaRyzenEFI

OpenCore 0.5.9 | Catalina 10.15.4 | Works perfectly fine with Ryzen 5 3600 & RX580 8GB and MSI B450 Tomahawk Max.

Did not tested 15.4+, Big Sur highly won't work with this EFI.

After installation, if you have sound issue then you have to try layouts. For that, 
• Open config.plist
• Find boot-args
• Change "alcid=1" by your sound card's layouts and restart.

Layout list:
https://github.com/acidanthera/applealc/wiki/supported-codecs
