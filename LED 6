ORG 0000H
SETB P0.0 ;switch configuration
SETB P0.1 ;switch configuration
SETB P0.2 ;led set
LOOP: CLR C
ORL C,/P0.0
ORL C,/P0.1
CPL C
MOV P0.2,C
SJMP LOOP
END
