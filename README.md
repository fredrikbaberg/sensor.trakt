[![Version](https://img.shields.io/badge/version-0.0.1-green.svg?style=for-the-badge)](#) [![mantained](https://img.shields.io/maintenance/yes/2018.svg?style=for-the-badge)](#)

[![maintainer](https://img.shields.io/badge/maintainer-Ian%20Richardson%20%40iantrich-blue.svg?style=for-the-badge)](#)

## Support
Hey dude! Help me out for a couple of :beers: or a :coffee:!

[![coffee](https://www.buymeacoffee.com/assets/img/custom_images/black_img.png)](https://www.buymeacoffee.com/zJtVxUAgH)

# A WORK IN PROGRESS

# sensor.personalcapital
[Trakt](https://www.trakt.tv) component for Home Assistant

To get started put `/custom_components/sensor/trakt.py` here:
`<config directory>/custom_components/sensor/trakt.py`

**Example configuration.yaml:**

```yaml
sensor:
  platform: trakt
  email: iantrich@email.com
  password: 12345
  days: 10
```

**Configuration variables:**

key | description
:--- | :---
**platform (Required)** | `trakt``
**email (Required)** | Email for trakt.com
**password (Required)** | Password for trakt.com
**days (Optional)** | How many days to look forward for movies/shows

***

Due to how `custom_components` are loaded, it is normal to see a `ModuleNotFoundError` error on first boot after adding this, to resolve it, restart Home-Assistant.