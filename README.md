# bsb-lan-home-assistant

Le mail de contact pour acheter la carte BSB LAN  : bsb@code-it.de
> [!IMPORTANT]
> Le fichier **BSB_LAN_custom_defs.h** peut être seulement si vous avez la même carte et PAC que moi. Dans le cas contraire, voir la vidéo.

La liste des codes à renseigner dans le BSB LAN pour l'envoi MQTT 
700,710,712,1600,1610,8000,8003,8006,8410,8412,8820,8821,8830,8314,8700,8740,3113,3124,3125

Si vous gardez le nom de répertoire, il faut ajouter les références des fichiers pour la conf mqtt dans le fichier configuration.yaml
```
mqtt:
    sensor: !include mqtt/sensor.yaml
    button: !include mqtt/button.yaml
    climate: !include mqtt/climate.yaml
    switch: !include mqtt/switch.yaml
    number: !include mqtt/number.yaml
```
