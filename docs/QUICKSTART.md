# Quick Start Guide

## For Rescue Teams (Server)

1. Connect to a local Wi-Fi network (hotspot or router)
2. Launch server_app.py or the RescueServer executable
3. The dashboard will show your LAN IP and start broadcasting for discovery
4. Monitor incoming messages from civilians in real-time

## For Civilians

1. Connect to the same local Wi-Fi network as the rescue team
2. Launch civilian_client.py or the RescueLink executable
3. Enter your name and click Connect - it will auto-discover the server
4. Send your location, status, images, or voice messages as needed

## Important Notes

- No internet connection is required
- Both devices must be on the same local network
- Broadcast port 50005, TCP port 5006
- Images received by server are saved in 
eceived_images/
