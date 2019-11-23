__Set/Read memory channel__

Set memory channel:

	MR p1,p2

Get memory channel:

	MR p1

Returns: `MR p2` or `N` if the band is not in memory channel mode (i.e. VFO)

| p1  | [Band](/tables/band.md) |
| --- | --- |
| 0 | Band A |
| 1 | Band B |

| p2  | Memory channel, 3 digits, 000-999 |
| --- | --- |
