# PalmID

Identify yourself with your `Palm ID`.

Use [`EDCC-Palmprint-Recognition`](https://github.com/Leosocy/EDCC-Palmprint-Recognition) and [`RobustPalmprintROI`](https://github.com/Leosocy/RobustPalmprintROI) to build a complete palmprint authentication system demo.

## Architecture

### Microservices

- PPIP(Palmprint Image Processing). Provide palmprint image/video detection, ROI extraction  services. 
- PPIC(Palmprint ID Center). Provide palmprint id registration, certification services.

### Web Framework

- flask

### RPC

- gRPC

serializer

- protobuf