### Wifi Analyzer

This is just an initialization of the project...as always, this repo is more of a learning exercise than anything else, sort of my "coding diary", for lack of a better term. ut I happen to pick up a lot of "toys" recently and looking to build some cool things with them...

### Project Description

One very useful endpoint of the Kismet Wireless API is the "Device views" endpoint. Specifically, when just getting started is the "Access point devies view":
`/devices/views/phydot11_accesspoints/devices.json`

This endpoint returns Wi-Fi access point devices _only_. Read more about it here: [Access points device view#](https://www.kismetwireless.net/docs/api/wifi_dot11/#access-points-device-view)

The other useful (and related) endpoing is the _"Wi-fi related devices"_ endpoint: `/phy/phy80211/related-to/{DEVICEKEY}/devices.json`. This endpoint will return an array of complete device records of the associated devices, for example the clients associated to a particular access point. These two endpoints are very useful for starting out with the Kismet Wireless API.

**Note**: Credit should go to [Introduction to Kismet Wireless REST API](https://www.youtube.com/watch?v=3LJo4RPT9JE) excellent YouTube videos on the Kismet REST APi for the above mentioned endpoints, I hope to build on this and add some additional functionality. If you are just getting started check out his videos, it'll save you some time.

---

## Technologies (to be) Used

### Software

[Node.js](https://nodejs.org/en/) - JavaScript runtime built on Chrome's V8 JavaScript engine

[Axios](https://axios-http.com) - Promise based HTTP client for the browser and node.js

[Kismet Wireless API](https://www.kismetwireless.net/docs/api) - Restful API for Kismet Wireless

### Hardware

[ALFA AWUS036ACM](https://www.amazon.com/Network-AWUS036ACM-Long-Range-Wide-Coverage-High-Sensitivity/dp/B08BJS8FXD) - ALFA AWUS036ACM 802.11ac Wi-Fi USB 3.0 adapter

[RTL-SDR V3](https://www.amazon.com/dp/B0BMKB3L47?th=1) - RTL-SDR V3 R860 RTL2832U Kit with 1PPM TCXO SMA F Software Defined Radio

[Particle Photon 2](https://store.particle.io/collections/wifi/products/photon-2-edge-ml-kit) - Photon 2 + Edge ML Kit

---

[Kismet](https://www.kismetwireless.net) is an 802.11 layer2 wireless network detector, sniffer, and intrusion detection system. Kismet will work with any wireless card which supports raw monitoring (rfmon) mode, and (with appropriate hardware) can sniff 802.11b, 802.11a, 802.11g, and 802.11n traffic. Kismet also supports plugins which allow sniffing other media such as ADSB (aircraft) traffic, GSM, LTE, and more.
