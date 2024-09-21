# Home Assistant Git Exporter

Export all of your Home Assistant configuration to a git repository of your choice.
Can be used to show your Home Assistant setup in public repositories.

![Addon Stage][stage-badge]
![Supports aarch64 Architecture][aarch64-badge]
![Supports amd64 Architecture][amd64-badge]
![Supports armhf Architecture][armhf-badge]
![Supports armv7 Architecture][armv7-badge]
![Supports i386 Architecture][i386-badge]

[![Add repository on my Home Assistant][repository-badge]][repository-url]
[![Install on my Home Assistant][install-badge]][install-url]
[![Donate][donation-badge]][donation-url]

# Functionality

* Export Home Assistant configuration.
* Export Supervisor Addon configuration.
* Export Lovelace configuration.
* Export ESPHome configurations.
* Export Node-RED flows.
* Check for plaintext secrets based on your `secrets.yaml` file and common patterns.
* Check for plaintext ip and addresses in your config.

# Example

For an example take a look at my own [Home Assistant configuration](https://github.com/Poeschl/home-assistant-config).
The folders there are gettings synced with this addon.

# Badge

If you export your config with this addon and want to help me to spread it further, here is a badge you can embed in your README.

[![Home Assistant Git Exporter](https://img.shields.io/badge/Powered%20by-Home%20Assistant%20Git%20Exporter-%23d32f2f)](https://github.com/Poeschl/Hassio-Addons/tree/main/git-exporter)

```markdown
[![Home Assistant Git Exporter](https://img.shields.io/badge/Powered%20by-Home%20Assistant%20Git%20Exporter-%23d32f2f)](https://github.com/Poeschl/Hassio-Addons/tree/main/git-exporter)
```


[stage-badge]: https://img.shields.io/badge/Addon%20stage-stable-green.svg
[aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-badge]: https://img.shields.io/badge/i386-yes-green.svg

[repository-badge]: https://img.shields.io/badge/Add-repository-41BDF5?logo=home-assistant&style=for-the-badge
[repository-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A//github.com/Poeschl-HomeAssistant-Addons/repository

[install-badge]: https://img.shields.io/badge/Install%20on-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[install-url]: https://my.home-assistant.io/redirect/supervisor_addon?addon=68413af6_git-exporter

[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl

