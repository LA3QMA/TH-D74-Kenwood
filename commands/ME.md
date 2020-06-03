__Set/Read memory channel__

Set memory channel:

	ME p1,p2,p3,p4,p5,p6,p7,p8,p9,p10,p11,p12,p13,p14,p15,p16,p17,p18,p19,p20,p21,p22,p23

Get memory channel:

	ME p1

Returns: ME p1,...,p23

| p   | Function |
| --- | --- |
|  1 | Memory channel number, 3 digits, 000-999
|  2 | Frequency in Hz, 10 digits, C clears the channel
|  3 | Offset frequency in Hz, 10 digits
|  4 | [Step size](/tables/step_size.md)
|  5 | [Transmit step size](/tables/step_size.md)
|  6 | [Mode](/tables/mode.md)
|  7 | [Fine mode](/tables/status.md)
|  8 | [Fine step size](/tables/finestep.md)
|  9 | [Tone status](/tables/status.md)
| 10 | [CTCSS status](/tables/status.md)
| 11 | [DCS status](/tables/status.md)
| 12 | [CTCSS/DCS status](/tables/status.md)
| 13 | [Reverse](/tables/status.md)
| 14 | [unknown probably 220MHz band? Tnx to: Travis KK4VCZ]
| 15 | [Shift direction](/tables/shift.md)
| 16 | [Tone frequency](/tables/tone_ctcss.md)
| 17 | [CTCSS frequency](/tables/tone_ctcss.md)
| 18 | [DCS frequency](/tables/DCS.md)
| 19 | [Cross encode/decode](/tables/cross.md)
| 20 | URCALL
| 21 | [D-Star squelch type](/tables/DSTAR_squelchtype.md)
| 22 | [D-Star squelch code](/tables/DSTAR_squelchcode.md)
| 23 | [Lock out](/tables/status.md)
