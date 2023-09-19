# bsb-lan-home-assistant

Le mail de contact pour acheter la carte BSB LAN  : bsb@code-it.de
> [!IMPORTANT]
> Le fichier **BSB_LAN_custom_defs.h** peut être seulement si vous avez la même carte et PAC que moi. Dans le cas contraire, voir la vidéo.

Si vous gardez le nom de répertoire, il faut ajouter les références des fichiers pour la conf mqtt dans le fichier configuration.yaml
```
mqtt:
    sensor: !include mqtt/sensor.yaml
    button: !include mqtt/button.yaml
    climate: !include mqtt/climate.yaml
    switch: !include mqtt/switch.yaml
    number: !include mqtt/number.yaml
```
