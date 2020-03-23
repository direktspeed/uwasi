# uwasi
A Universal WASI written in rust to run on any platform exposes a WASI Pollyfill that uses http2 or grpc to offer a Universal abstracted server based OS. It is the backbone of the upwa(open pwa) Project that will offer PWA installation Caps for any system.

- JS=>WASI=>NativOS
- JS=>WasmerJS=>NativOS
- JS=>uwasi=>NativOS

uwasi will offer a https based permission api open pwa

## WHY?
I got the idea long time ago but now the Dependencies are solved and we can start Implamentation. We Need a Universal Platform to run our Applications with less overhead. This Also Will Replace Projects like Electron as this offers a single instance to expose Caps (file access, network access, hardware access, remote*)
