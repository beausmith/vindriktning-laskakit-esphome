# Air Quality Sensor

This is my ESPHome configuration file for the [LaskaKit ESP-VINDRIKTNING ESP-32](https://www.laskakit.cz/laskakit-esp-vindriktning-esp-32-i2c/) integrated with Home Assistant.

## Hardware 
- [Ikea Vindriktning](https://www.ikea.com/us/en/p/vindriktning-air-quality-sensor-60515911/)
- [LaskaKit ESP-VINDRIKTNING ESP-32](https://www.laskakit.cz/laskakit-esp-vindriktning-esp-32-i2c/)
- [LaskaKit SCD41](https://www.laskakit.cz/laskakit-scd41-senzor-co2--teploty-a-vlhkosti-vzduchu/)

## Usage in ESPHome
1. Use the [vindriktning.yaml](esphome/packages/vindriktning.yaml) contents for your custom sensor.
2. Include the vindriktning.yaml as a package as in [kitchen_air_quality.yaml](esphome/kitchen_air_quality.yaml).
