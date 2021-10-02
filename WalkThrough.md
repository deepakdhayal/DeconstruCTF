# DeconstruCTF
WalkThrough
This is my First Time writting a walkthrough. There can be mistakes. Suggestions are Welcomed.


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


##Taxi Union Problems 

![1](https://user-images.githubusercontent.com/48149717/135705514-0d1de0b2-e52f-419c-b932-996280e4b770.jpg)

1. There is only one input field in the website.

![2](https://user-images.githubusercontent.com/48149717/135705545-20adda77-482c-4487-9b6a-b7a84adf69f8.jpg)

2.If we put an (') in the field we can see an error. Its an SQL injection. Sql Injection Verified.

![4](https://user-images.githubusercontent.com/48149717/135705644-623ae09a-a7fb-4e76-b316-748573540ae1.jpg)

3. Intercept the request in burpsuit.

![5](https://user-images.githubusercontent.com/48149717/135705688-3b036575-1edf-4c1a-b306-44c2d4fe3220.jpg)

4. copy the request and save it in a file and use SQLmap.
![6](https://user-images.githubusercontent.com/48149717/135705724-a77098c4-58aa-4845-8569-998d1edf8c80.jpg)

![7](https://user-images.githubusercontent.com/48149717/135705735-f1378493-d988-47ef-99e0-51535f33b346.jpg)

![8](https://user-images.githubusercontent.com/48149717/135705737-4d5254f9-913f-4507-a9ad-209f6be97b36.jpg)

5. Location is being displayed in the last image. Use the hint no caps.

![9](https://user-images.githubusercontent.com/48149717/135705812-0e64ce33-40c9-4b5b-94a7-937dd7ce5b65.jpg)


##RSA - 1 

![1](https://user-images.githubusercontent.com/48149717/135706052-3c72c8b6-5767-4d8f-8c47-5c41670d02a7.jpg)


##RSA - 2

![1](https://user-images.githubusercontent.com/48149717/135706058-7da52a8b-932e-47ca-9516-e6d27feb2a76.jpg)


![2](https://user-images.githubusercontent.com/48149717/135706062-544f3c8e-2b2f-4d87-87e8-144beb3acce0.jpg)

##Scraps 

![scrap](https://user-images.githubusercontent.com/48149717/135706224-3c411b30-93ce-490d-abf2-8d0b5f0381dd.jpg)

Base64 Decode

![scra2](https://user-images.githubusercontent.com/48149717/135706231-3a35cbbf-b8c8-4ec7-8ede-ef8697d40c99.jpg)


##Failed Logins 
My approach might not be correct but it worked in this case.

1.Rename the apk file:::: using ---mv chall.apk chall.zip

2. d2j-dex2jar -d chall.zip

3. jd-gui chall-dex2jar.jar
 
![failed login](https://user-images.githubusercontent.com/48149717/135706281-0cc72a9d-5e33-4b47-a8c5-d20e2dfdd6e1.jpg)

![failed login1](https://user-images.githubusercontent.com/48149717/135706287-5571eb44-5c5e-4173-a342-0e80c43b4824.jpg)

