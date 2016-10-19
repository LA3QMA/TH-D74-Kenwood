__Set/Read the TNC mode__

Set TNC:

	TN p1,p2

Read the TNC mode:

	TN
	
Returns: p1,p2

|p1|function
|---|---|
|0|Off
|1|APRS
|2|KISS

|p2|function
|---|---|
|0|Band A
|1|Band B


__Not possible to get out off KISS mode__
*Maybe sending the KISS exit command: C0 FF C0 (have to try this)*
