# CW Radar Recordings

These are raw CW radar recordings made by a modified Hi-Link LD2415H vehicle speed radar.

[Reverse Engineering was done by me before](https://www.dm5tt.de/2025/02/15/reverse-engineering-hilink-ld2415h/).

# Configuration

Radar:
 - Frequency: ~24.125GHz
 - EIRP: ~18dBm


ADC
* 2 Byte per sample (uint16_t)
* 16 Bit ADC resolution
* 50kHz ADC speed
* V_aref = 3.3V

The parameters of the antenna can be found if you google for the "HLK-LD2415" datasheet.

The transmitter/antenna itself wasn't modified.

# Recording Chain

![Recording Chain](docs/cw_setup.drawio.png)

# Setup Verification

![Recording Chain](docs/cw_calibration.jpeg)

Radar test against the loudspeaker membrane that generated a sinus on 50Hz/100Hz/150Hz/200Hz.


# Recording examples



## street_low_gain_1741464109_1741465109_3


![Street High Gain Screenshot](recordings/street_high_gain/street_low_gain_1741464109_1741465109_3.jpeg)

```
1741443997 = Unix Timestamp Start
1741444997 = Unix Timestamp Stop
4          = Segment Number
``````

