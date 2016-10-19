__Set/Read APRS beacon type__

Set the APRS beacon type:

	BE n

Get the APRS beacon type:

	BE

BE sends a beacon when the mode is *manual*

BE sends a beacon after the PTT is used if the mode is *PTT*

BE toggles a beacon on/off if the mode is *auto*

BE toggles a beacon on/off if the mode is *SmartBeacon*

Returns N if TNC is OFF
	
|n|APRS beacon type
|---|---|
||toggles on/off
|1|manual
|2|PTT
|3|Auto
|4|SmartBeacon