---
sidebar_position: 12
---

# GPS

The correct term to use is GNSS.

GPS is just one of the available Global navigation satellite systems.

## Protocol

Enable and set up the GNSS settings:

| Protocol | Description                                      |
| :------- | :----------------------------------------------- |
| NMEA     | A binary protocol for GNSS data                  |
| UBLOX    | A text protocol for GNSS data, more customizable |
| MSP      | GNSS using the MultiWii Serial Protocol          |

## Settings

| Setting             | Description                                                                                                                                         |
| :------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| Auto Baud           | Automatically detect the baud rate of the GNSS                                                                                                      |
| Auto Config         | Automatically configure the GNSS                                                                                                                    |
| Set Home Point Once | If enabled, the home point will be set only once, when a fix is acquired. If disabled, the home point will be updated every time the craft is armed |

For more information about GPS changes in 4.5, see the [Wiki document](/docs/wiki/guides/current/Failsafe).
