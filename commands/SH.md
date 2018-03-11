__Set/Read filter cutoff/width__

Set filter cutoff/width:

	SH p1,p2

Get filter cutoff/width:

	SH p1

Returns: SH p1,p2

| p1  | Mode |
| --- | --- |
| 0 | SSB |
| 1 | CW  |
| 2 | AM  |

| p2  | SSB High Cut | CW Width | AM High Cut |
| --- | -------------| -------- | ----------- |
| 0 | 2.2 kHz | 0.3 kHz | 3.0 kHz |
| 1 | 2.4 kHz | 0.5 kHz | 4.5 kHz |
| 2 | 2.6 kHz | 1.0 kHz | 6.0 kHz |
| 3 | 2.8 kHz | 1.5 kHz | 7.5 kHz |
| 4 | 3.0 kHz | 2.0 kHz | N       |
