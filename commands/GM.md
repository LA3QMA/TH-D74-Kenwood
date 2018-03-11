__Set/Read radio/GPS mode__

Set radio/GPS mode:

	GM p1

Get radio/GPS mode:

	GM

Returns: p1

| p1  | Function |
| --- | --- |
| 0 | Operating Mode: *Normal* (Radio and internal GPS)            |
| 1 | Operating Mode: *GPS Receiver* (Radio off, GPS-only-mode on) |

Setting the mode automatically restarts device in new mode.
