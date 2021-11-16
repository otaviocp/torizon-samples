# Multi-display

There are two ways to run multi-display samples:

* Using a single DRM interface that outputs to multiple displays.
* Using two DRM interfaces, each of them outputs to a different display.

To learn more about this topic, including what is supported by your hardware,
please refer to [Working with Weston on TorizonCore: Multi-display](https://developer.toradex.com/knowledge-base/working-with-weston-on-torizoncore#Multidisplay).

## Single DRM interface

The sample is located on the directory `single-drm-interface`. Copy the Docker
Compose to the board and start it with `docker-compose up`.

## Dual DRM interface

The sample is located on the directory `dual-drm-interface`. Copy the Docker
Compose to the board and start it with `docker-compose up`.