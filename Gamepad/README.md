- Why need 8 gamepad support ?
Natively, browsers actually support 4 gamepad (Navigator.getGamepads)
If you eager to make 3VS3 or 4vs4, this executable is fit for your request.

- How to install it?
Follow the pre-install recommandation here.
Just run the "main.exe"(Windows 64bits only), connect your gamepads, and go to "Stars tournament".

- The current software provide you 8 gamepad support, how does it works ?
1. CPP application get the list of connected gamepad through SDL2. It send the datas to NodeJS with TCP socket protocol.
2. NodeJS have an intermediate role, it send the data to local websocket "ws://127.0.0.1:4443"
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
