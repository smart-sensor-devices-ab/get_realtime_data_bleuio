# Export data from bluetooth devices

This script helps you get realtime data from ble devices and show it on web browser.

## Requirments

- [BleuIO](https://www.bleuio.com/) - BLE usb dongle
- Chrome 78 or later and you need to enable the
  **#enable-experimental-web-platform-features** flag in **chrome://flags**  
  Open **chrome://flags/#enable-experimental-web-platform-features** in Google Chrome browser.

## Instructions

- Clone the repository
- Connect the dongle to your computer
- open index.html file
- Click connect and wait for the device to load on your com port.
- Select your com port.
- Scan for BLE devices. (this script only scan for Hibou Devices . you
  can change the manufacturer value at script.js file)
- Select device and start getting data.
- You can set data collection interval from script.js file

  You can use this data to create chart, export or upload in cloud if necessary.
