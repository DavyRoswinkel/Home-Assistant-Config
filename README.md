# Home-Assistant-Config

Nederlandstalige pollen informatie voor je Home assistent.

https://github.com/huizebruin/Home-Assistant-Config/blob/main/sensors/ambee-nl.yaml  deze code plaats je in je configuration.yaml
![ambee-hooikoort-homeassistant](https://user-images.githubusercontent.com/62996429/114306196-63559300-9adb-11eb-8627-eba67729126e.jpg)
En deze code vul je bij het toevoegen van een nieuwe kaart ( kies je de onderste opitie) om yaml code toe te voegen
![afbeelding](https://user-images.githubusercontent.com/62996429/114317312-c2c99800-9b07-11eb-8cd4-81bfc91f1788.png)

Veel plezier ermee .




*************************************************************
Het thema welke ik gebruik voor Home assistant
/themes/Huizebruin/Huizebruin (Dark).yaml
![huizebruin-home assistant](https://user-images.githubusercontent.com/62996429/114280723-ef63ae00-9a3a-11eb-9b42-49173f5d1e15.jpg)

En dan maak je een automation 
Set theme at startup
![afbeelding](https://user-images.githubusercontent.com/62996429/114281085-9d238c80-9a3c-11eb-8c01-1eec0106d6f6.png)

alias: Set theme at startup
trigger:
  - platform: homeassistant
    event: start
action:
  - service: frontend.set_theme
    data:
      name: Huizebruin (Dark)
mode: single

Nu zal bij elke herstart deze thema geladen worden.




*************************************************************
Liked some of my work? Buy me a coffee (or more likely a beer)

<a href="https://www.buymeacoffee.com/huizebruin" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

