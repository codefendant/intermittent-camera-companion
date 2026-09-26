# Intermittent Camera Companion

Intermittent Camera Companion (ICC) is a Home Assistant custom integration for battery/intermittent cameras, including Reolink Argus MagiCam/Home Hub compositions, stable RTSP presentation, retained HOLD frames, Frigate coordination, and optional process-camera observations.

## Home Assistant 0.1.0

Release asset name:

`intermittent_camera_companion-ha-0.1.0.zip`

After the `v0.1.0` release asset is published, install from Home Assistant Terminal & SSH with:

```bash
cd /config
wget -O intermittent_camera_companion-ha-0.1.0.zip \
  https://github.com/codefendant/intermittent-camera-companion/releases/download/v0.1.0/intermittent_camera_companion-ha-0.1.0.zip

rm -rf custom_components/intermittent_camera_companion
unzip -o intermittent_camera_companion-ha-0.1.0.zip
ha core restart
```

Then open **Settings → Devices & services → Add integration** and select **Intermittent Camera Companion**.

## Verified package

The PR 32 Home Assistant 0.1.0 package was built and tested as a self-contained integration.

SHA-256:

`6fe726d9b73e30d0a17638d28ebc42c767922807751d8460539ea8fecf09c45e`

The package contains the integration at:

`custom_components/intermittent_camera_companion/`
