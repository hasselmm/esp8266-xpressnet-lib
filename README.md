# esp8266-xpressnet-lib
XpressNet library from Philipp Gahtow converted to run on ESP8266 with an RS485 interface via software serial as ESP8266 does not support 9bit harware serial.

Under development.

### XpressNet (RS485) pin layout
| ESP8266 | Variable       | Description |
|---------|----------------|-------------|
| GPIO2   | `XNetRS485_RX` | RX          |
| GPIO4   | `XNetRS485_TX` | TX          |
| GPIO5   | `RS485_TXRX_PIN` |TX Control (optional) |