# DeconstruCTF
WalkThrough


##Pirates

![pirate](https://user-images.githubusercontent.com/48149717/135705254-1d60b22e-dced-49aa-b67b-0a45673b65dc.jpg)
1. open file in wireshark.
[network_listen.pcap.zip](https://github.com/Nikdhayal/DeconstruCTF/files/7270930/network_listen.pcap.zip)
2. Follow TCP stream. 
![Pirates](https://user-images.githubusercontent.com/48149717/135705311-8044c1dd-a96d-48c7-a72b-6dc4d8554a03.jpg)


##The Missing Journalist


![missing](https://user-images.githubusercontent.com/48149717/135705352-e680b3eb-afed-4466-bc69-e353c1e93a2e.jpg)
1. File can be downloaded here.
[the_journalist.gif.zip](https://github.com/Nikdhayal/DeconstruCTF/files/7270932/the_journalist.gif.zip)
2. Extract the file.
![missingjournalist](https://user-images.githubusercontent.com/48149717/135705386-1628e7b2-9518-49c9-ae50-9b8e60cb0ab1.jpg)
3. Using foremost tool, you can see another PDF.
using Exiftool you can see a base64 string which is used as password for the last pdf.
![missingjournalist1](https://user-images.githubusercontent.com/48149717/135705405-36b75b6a-1f7d-40d7-83d0-a263d8e4669f.jpg)
