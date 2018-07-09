# PalmID

Identify yourself with your `Palm ID`.

Use `Palmprint Image Processor` and `Palmprint Codec` to build a complete palmprint authentication system demo.

- `Palmprint Image Processor`:
    1. Palm detection
    1. Palmprint ROI extraction
- `Palmprint Codec`

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