## Schritt-für-Schritt Anleitung: 

Verbindet Euch jetzt von der Kommandozeile oder einem Terminal-Fenster aus per SSH mit dem Pi, indem Ihr

`ssh pi@raspberrypi`

eingebt. Die Meldung könnt Ihr mit „yes“ bestätigen. 

Das Passwort lautet standardmäßig „raspberry“. Das könnt Ihr bei Bedarf nach dem Login mit dem Befehl `passwd` ändern.


![MicrosoftTeams-image (11)(1)](https://user-images.githubusercontent.com/89446428/139813644-96e0cb7e-ca27-4065-8680-eb661c10c51f.jpg)

Danach solltet Ihr noch die üblichen Raspberry-Pi-Updates einspielen:

`sudo apt-get update`

`sudo apt-get full-upgrade`

Das Full Upgrade kann eine Weile dauern. 

Anschließend könnt Ihr den Pi mit
`sudo reboot`
einmal neu starten.

![MicrosoftTeams-image (3)](https://user-images.githubusercontent.com/89446428/138842658-8d57187f-65f1-4912-9861-3fa60d2cbd12.jpg)

Nun geht es an die Installation des Router-Tools RaspAP.  Gebt dafür
`curl -sL https://install.raspap.com | bash` ein. 
Die Installation startet jetzt und kann eine kleine weile dauern. Meldungen können mit Y bestätigt werden. 

Ist die Installation erfolgreich gewesen, wird er euch nach einem Neustart fragen. Bestätigt dies wieder mit einem Y. 

![MicrosoftTeams-image (5)](https://user-images.githubusercontent.com/89446428/138842645-4b5d3818-e091-42b5-b7d0-e1172e4de27b.jpg)

Hier sollte der Pi als WLAN namens `raspi-webgui` auftauchen. Ihr könnt Euch mit dem Passwort `ChangeMe` mit dem WLAN verbinden.

![MicrosoftTeams-image (6)](https://user-images.githubusercontent.com/89446428/138841017-d02363cf-2aad-4524-8b84-c52426d5c29f.png)


![MicrosoftTeams-image (7)](https://user-images.githubusercontent.com/89446428/138842332-8f780cd0-e940-4a5c-88d7-ed82d90c345e.jpg)


![MicrosoftTeams-image (9)](https://user-images.githubusercontent.com/89446428/138843416-3c832a6e-d800-4748-93f8-61301b383b01.jpg)


![MicrosoftTeams-image (10)](https://user-images.githubusercontent.com/89446428/138843424-e1f35be6-6115-49dd-9514-a7046014eff6.jpg)


![MicrosoftTeams-image (8)](https://user-images.githubusercontent.com/89446428/138842948-fd450bcb-ec31-4ed7-8ca7-703c2d03a6f5.jpg)
