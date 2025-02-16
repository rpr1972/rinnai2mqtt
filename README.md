# Rinnai tankless water heater integration with Home Assistant

The purpose of this image is to provide an MQTT integration for Rinnai tankless water heaters in Home Assistant. Be aware that not all Rinnai tankless water heaters are supported - they must have some kind of "Wi-Fi module" attached. Besides that, this software was tested in a subset of models available - precisely the models of the so called "Digital Line": E17, E21, E27 and E33. These models are all **made in Brazil**, so it is very likely that this integration only works with devices made in Brazil.

Being a docker image, it is perfect for those who use Home Assistant in docker version: just install one more container and you're good to go (just like the container for MQTT that you probably already have). For those using Home Assistant OS, Supervised or Core, **it can run as an add-on**: just add this repository to Home Assistant OS add-ons repository and install it.

Some screenshots:

![thermostat](https://github.com/rpr1972/images/assets/139033678/06a7cdae-acbc-45c5-818b-f315b9a40779?raw=true)

![screenshot](https://github.com/rpr1972/rinnai2mqtt/assets/139033678/b200e1de-5822-4537-ac8e-3f9f348e931b?raw=true)

You can find more information about the integration on project's docker hub: https://hub.docker.com/r/robrosa/rinnai2mqtt
