# MEMO013-Robot
LDX #$00
LDA $0C10,X
JSR $FFD2
INX
CPX #$2B
BNE $0B02
RTS
BANK 15
SYS DEC("0B00")
BSAVE "HELLO WORLD", P2816 TO P3136
LOAD "HELLO WORLD",8,1
