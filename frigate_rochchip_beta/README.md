# Home Assistant Add-on: Frigate Rockchip Beta (0.13.0)

Please reference the [release notes](https://github.com/blakeblackshear/frigate/releases) for breaking changes.

![Supports aarch64 Architecture][aarch64-shield]

NVR with realtime local object detection for IP cameras.

You must create a config file as `frigate.yml` in the root of your Home Assistant configuration directory.

Use directory path starting with `/config` like `/config/frigate.db` for the database.

For preliminary config for rockchip follow this documentations link: https://deploy-preview-6262--frigate-docs.netlify.app/configuration/object_detectors/#rockchip-rknn-toolkit-lite2

This version of the add-on requests full device access in order to turn off protection mode for those devices which don't work with protection mode enabled.

[Documentation](https://docs.frigate.video)

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
