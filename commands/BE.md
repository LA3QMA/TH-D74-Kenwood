__Send APRS beacon__

Transmit APRS beacon:

	BE

| [Mode](PT.md) | Action |
| --- | --- |
| Manual         | BE sends a beacon                   |
| PTT            | BE sends a beacon after PTT is used |
| Auto           | BE toggles beacon on/off            |
| SmartBeaconing | BE toggles beacon on/off            |

Returns: BE if accepted or N if TNC is off

If no callsign ("NOCALL") is set, no beacon will be sent.

The mode is set using the [PT](PT.md) command.
