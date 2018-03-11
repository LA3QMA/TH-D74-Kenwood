__Set/Read TNC mode__

Set TNC mode:

	TN p1,p2

Get TNC mode:

	TN

Returns: p1,p2

| p1  | Function |
| --- | --- |
| 0 | Off  |
| 1 | APRS |
| 2 | KISS |

| p2  | Band |
| --- | --- |
| 0 | Band A |
| 1 | Band B |


__Not possible to get out of KISS mode__
*Maybe sending the KISS exit command: C0 FF C0 (have to try this)*
