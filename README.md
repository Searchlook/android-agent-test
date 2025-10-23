# android-agent-test
Hiring challenge for the new project DIP

Problem Statement
Build a minimal Android app that:

Connects to WebSocket server at wss://echo.websocket.org
On boot, auto-starts and sends: {"deviceId": "test_001", "status": "online"}
Receives JSON commands: {"command": "getDeviceInfo"}
Executes shell command: getprop ro.product.model
Returns result via WebSocket: {"result": "Pixel 5"}
Keeps running as foreground service with persistent connection

Deliverables (48 hours)

APK file
Source code (GitHub repository)
Screen recording video (2-3 min) showing:

App installation
Boot behavior (restart phone, app auto-starts)
WebSocket connection established
Command execution demo
Reconnection after airplane mode toggle


README.md with brief technical approach
