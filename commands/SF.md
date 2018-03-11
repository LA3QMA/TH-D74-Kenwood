__Set/Read step size__

Set step size:

	SF p1,p2

Get step size:

	SF p1

Returns: SF p1,p2

| p1  | [Band](/tables/band.md) |
| --- | --- |
| 0 | Band A |
| 1 | Band B |


Version Euro E,5:

| p2  | [Step size](/tables/step_size.md) |
| --- | --- |
| 0 | 5 kHz    |
| 1 | 6.25 kHz |
| 2 | 8.33 kHz |
| 3 | 9 kHz    |
| 4 | 10 kHz   |
| 5 | 12.5 kHz |
| 6 | 15 kHz   |
| 7 | 20 kHz   |
| 8 | 25 kHz   |
| 9 | 30 kHz   |
| A | 50 kHz   |
| B | 100 kHz  |

8.33 kHz is limited to range 108.000 - 135.999

9 kHz is limited to range 0.100 - 1.709

50 kHz is the only step size in range 76.000 - 107.999


Version Euro E,6:

| p2  | [Step size](/tables/step_size.md) |
| --- | --- |
| 0 | 5 kHz    |
| 1 | 6.25 kHz |
| 2 | N        |
| 3 | N        |
| 4 | 10 kHz   |
| 5 | 12.5 kHz |
| 6 | 15 kHz   |
| 7 | 20 kHz   |
| 8 | 25 kHz   |
| 9 | 30 kHz   |
| A | 50 kHz   |
| B | 100 kHz  |
