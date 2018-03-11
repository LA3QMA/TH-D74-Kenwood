__Set/Read GPS sentence__

Set GPS sentences output status:

	GS p1,p2,p3,p4,p5,p6

Get GPS sentences output status:

	GS

Returns: GS p1,p2,p3,p4,p5,p6

| p1  | $GPGGA sentence status |
| --- | --- |
| 0 | Off |
| 1 | On  |

| p2  | $GPGLL sentence status |
| --- | --- |
| 0 | Off |
| 1 | On  |

| p3  | $GPGSA sentence status |
| --- | --- |
| 0 | Off |
| 1 | On  |

| p4  | $GPGSV sentence status |
| --- | --- |
| 0 | Off |
| 1 | On  |

| p5  | $GPRMC sentence status |
| --- | --- |
| 0 | Off |
| 1 | On  |

| p6  | $GPVTG sentence status |
| --- | --- |
| 0 | Off |
| 1 | On  |
