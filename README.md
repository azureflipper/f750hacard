A simple HA card for a F750/F730 heat pump

Requires: https://github.com/elupus/hass_nibe integration

Instruction:
- Setup nibe integration
- Setup template "static" sensor in order to support conditional icon for heating priority (or skip this conditional entity).
  - In your config file add contents of: template.yaml
- Upload drawing to hass (./www/f750-hass-drawing.png)
- Create a Picture elements card, paste yaml

Preview of picture elements card in hass:

![preview](https://user-images.githubusercontent.com/38658285/214054975-1f273aaf-3628-4892-a620-f80fcbb6f639.png)
