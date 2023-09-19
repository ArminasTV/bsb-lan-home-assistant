# bsb-lan-home-assistant

Si vous gardez le nom de répertoire, il faut ajouter les références des fichiers pour la conf mqtt dans le fichier configuration.yaml

mqtt:
    sensor: !include mqtt/sensor.yaml
    button: !include mqtt/button.yaml
    climate: !include mqtt/climate.yaml
    switch: !include mqtt/switch.yaml
    number: !include mqtt/number.yaml
