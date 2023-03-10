A simple HA card for a F750/F730 heat pump

Requires: https://github.com/elupus/hass_nibe integration

Instruction:
- Setup nibe integration
- Setup template "binary" sensor in order to support conditional icon for heating priority (or skip this conditional entity).
  - In your config file add contents of: template.yaml
- Upload drawing to hass (./www/f750-hass-drawing.png)
- Create a Picture elements card, paste yaml
- Change the first 5 numbers in every entity to your Nibe systemID

Preview of picture elements card in hass:

![preview](https://user-images.githubusercontent.com/38658285/214054975-1f273aaf-3628-4892-a620-f80fcbb6f639.png)

I'm using mine as part of a vertical stack like this:

![image](https://user-images.githubusercontent.com/38658285/214058282-efd38b9d-0175-4830-b62d-d72c2501b6dc.png)
